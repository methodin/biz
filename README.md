# biz
Business spec matching to code


* 1 User signup
    * 1.1 The user is presented with a signup form
    * 1.2 User should be able to signup with email address and password
    * 1.3 Their email address should be validated against fraud checks and their account should be flagged if fraud check fails
    * 1.4 The user should receive a validation code for email validation once past fraud checks
    
    
```php
// biz-block 1
class SignupForm {
  public function getFields() {
    // biz 1.1
    return ['email', 'password'];
  }
}
```

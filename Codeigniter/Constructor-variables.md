[Codeigniter] Constructor variables
====================================

### Setting variable
```php
// Constuctor
public $Variable = array();

function __construct() {
  parent::__construct();
  $this->Variable = "Variable;"
}
// END constructor
```

### Call variable
```php
public function Call() {
  echo $this->Variable;
  // Output: Variable;
}

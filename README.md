Tel
===

Make tel: links alert the phone number on devices that can't make calls

<a href='http://drewtotango.com/tel'>drewtotango.com/tel</a>

### Basic usage

```javascript
$("body").tel();

or

$("a").tel({
  callback:function(phoneNumber) {
    // do something with phoneNumber
  }
});
```

### Default Options

```javascript
{
  callback : function(phoneNumber) {
    alert(phoneNumber)
  }
}
```

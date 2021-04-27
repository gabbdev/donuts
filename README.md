# EasyDB
> A php system for store everything locally in a practical way.


## What for?
The system was based on the super simple way to save what you need without needing several lines that fill the screen.

## Resources
- 🧠 **Super** fast, no crashes.
- 📚 **Organized** php code.
- 🎊 Save strings, images and objects **without losing definition**.
- 🔧 **Practical** installation.

## How to use

### 🔨 Installation
- To get started, download the `easydb` file and place it in the folder where your php code is.
- After that, insert this into your php code:
```php
require 'easydb';
```
- The installation is already finished! time to learn to use.

> 💡 EasyDB changes the permission of the database.json file automatically, if the file permissions are not `644`, change it manually.

The system is based on 2 things, tag and value.
For you to save an item, you need to define the tag, I will define as an example "fruit", now you will define the value, I will give the example as "banana".
```php
_store ("fruit", "banana");
```
it will return true, so you can use it in the if without additional text. now if i want to get this value i will define only the tag, which was fruit.
Would be like this:
```php
echo _get ("fruit");
```
it will return the value that I had set before: `banana`
If I want to delete the `fruit` from the database, I will give an example below:
```php
_delete("fruit");
```

I hope that you enjoyed. (✿◠‿◠)



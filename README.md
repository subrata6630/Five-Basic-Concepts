# The Five Basic Concepts of any Programming Language 

•	variable <br>
•	if/else <br>
•	Array <br>
•	Loop <br>
•	Function



### ভেরিয়েবল (variable):

ভেরিয়েবল হল একটা ধারক বা পাত্রের মত অথব ভ্যারিয়েবল হচ্ছে একটি পাত্র বা বাক্স যেখানে আপনি ভ্যালু বা ডাটা রাখতে পারবেন।  কোন একটা জিনিস ভ্যারি করলে প্রোগামিংয়ের ভাষা ভেরিয়েবল বলে। Vary-ভ্যারি করে বা চেইঞ্জ হয়, able-যোগ্য বা হতে পারে, variable- ভ্যারি করার যোগ্য বা চেইঞ্জ হতে পারে।

উদাহরন: রিক্সা ভাড়া
```php
<?php
$txt = "Hello world!";
$x = 5;
$y = 10.5;
?>
```

### এবার চল দেখে নেওয়া যাক variable এর type বা Data type কি?

স্ট্রিং: লেখা বা স্ট্রিং হচ্ছে বর্ণের সমস্টি যেমন আমাদের নাম একটি স্ট্রিং “আলম” , পুরো নাম “হিরো আলম” এখানে দুটি শব্দ এটি ও একটি স্ট্রিং ।

ডাটা টাইপকে ছয় শ্রেণীতে বিভক্ত করা যায়। যথা

* Intiger (ইন্টিজার)
* Float / Double (ফ্লট বা ডাবল)
* Boolean (বুলিয়ান)
* String (স্ট্রিং)
* Array (এরে)
* Object (অবজেক্ট)


### if/else (শর্তাধীন/ কন্ডিশন):
শর্ত সাপেক্ষে কোন কিছু করাকে প্রোগ্রামিং এর ভাষায় কন্ডিশন বা কন্ডিশনাল স্টেটমেন্ট বলে। কোনো শর্তের উপর কোনো action নেয়ার জন্য কন্ডিশনাল স্টেটমেন্ট ব্যাবহৃত হয়। ধরুন আমি আমার ওয়েবসাইটে এমন একটা ফিচার  যোগ করতে চাই যাতে যদি কেউ আমার সাইটে দুপুর ১২ টার আগে ঢুকে তাহলে দেখাবে “Good Morning” আর যদি কেউ বিকেল ৫ টার পর ঢুকে তাহলে দেখাবে “Good evening” এই ধরনের বরং এর চেয়েও মজাদার ও অ্যাডভান্সড কাজগুলো করতে Conditional statement এর দরকার। যদি কোন কিছু সত্য হয়, তাহলে একটা কিছু কোড রান করার জন্য if স্ট্যাটমেন্ট ব্যবহার করা হয়। 

 ### In PHP we have the following conditional statements:

* if statement - executes some code if one condition is true
* if...else statement - executes some code if a condition is true and another code if that condition is false
* if...elseif...else statement - executes different codes for more than two conditions
* switch statement - selects one of many blocks of code to be executed

``` php
if (condition) {
  code to be executed if condition is true;
}
```


``` php
<?php
$t = date("H");

if ($t < "20") {
  echo "Have a good day!";
}
?>
```

### Array/ Collection (সমষ্টি)এ্যারে কি?:  
এক সাথে কোন কিছুর Collection পাওয়াকে কে Array বলে। এ্যারে নিয়ে কাজ করতে অনেক ধরনের জরুরী ফাংশনালিটি প্রয়োজন তাদের মধ্যে কিছু বেটা ভার্সনে ইম্পলিমেন্ট করা হয়েছে।

এ্যারে হলো পিএইচপি এর একটি ফাংশন। যা একাধিক ভ্যারিয়েবল কে একটি এ্যারে এর মধ্যে সংরক্ষণ করে রাখে । 
Array ৩ প্রকার : যথাঃ- 
Index Array,<br>
Associative Array, <br>
Multidimesional Array<br>

যেমন : আপনি কতগুলো রংয়ের এর নাম একটি ভ্যারিয়েবল এর রাখতে তাহলে আপনাকে পিএইচপি এর এ্যারে ফাংশন ব্যবহার করতে হবে । যদি না করেন তাহেল আপনাকে প্রতিটি রংয়ের জন্য একাধিক ভ্যারিয়েবল লিখতে হবে।


উদাহরন: এক ডজন কমলা
```php
<?php
$cars = array("Volvo", "BMW", "Toyota");
echo "I like " . $cars[0] . ", " . $cars[1] . " and " . $cars[2] . ".";

```

### Loop (লুপ):

লুপ বা রিপিটেশন মানে হচ্ছে একই কাজ বারবার করা। লুপ এর কথা মাথায় আসলেই আমরা একটা বৃত্তের কথা চিন্তা করি, অথবা ইনফিনিটি সাইনের কথা চিন্তা করি। প্রোগ্রামিং এর লুপ হচ্ছে একই কাজ বার বার না করে একবার কাজটা করে যতবার খুশি ততবার রিপিট করার একটা মাধ্যম।

লুপ হচ্ছে এমন একটি কমান্ড যার সাহায্যে একটি কাজ অনেক বার করা যায়। লুপিং এর কাজে সবছেয়ে বেশি ব্যবহৃত হয় for loop. এ for loop এর তিনটি অংশ রয়েছে। তার আগে আমরা দেখেনি for loop সাধারন ব্যবহার নিয়ম।

উদাহরন: প্রোগ্রামিং এর সবচে' অসাধারণ ব্যাপার হচ্ছে কি, যদি তোমার একই কাজ বার বার করতে হয়, সেটা তুমি লুপে ফেলে করে ফেলতে পারো। ধরো, হুকুশ পাকুশ একদিন ভুলে গেলো ক্লাসে হোমওয়ার্ক করে নিতে। তখন ম্যাডাম ওকে বললো, তোমাকে এক হাজার বার লিখে আনতে হবে যে তুমি প্রতিদিন হোমওয়ার্ক করবে। হুকুশ পাকুশ ভাবলো সে যদি একটা লাইন লিখে সেটাকে বারবার করে কপি করে, তাহলেও গুনে গুনে এক হাজার বার কপি করতে হবে। কত্ত ঝামেলা, তাই না?

এবার চিন্তা করো, এটা আমরা হাতে হাতে কিভাবে করতাম? ধরো আমি শীতের ছুটি কাটাতে যাবো দাদুবাড়িতে - আমাকে দশটা জামা নিতে হবে কারণ আমি পুরো মাসটা সেখানে থাকবো। আমি করবো কি একটা একটা করে জামা নিবো, আর হাতে গুনবো আমি কয়টা জামা নিয়েছি। যখন দেখবো আমার হাতের আঙ্গুল গোনায় দশটা হয়ে গেছে তখন আমি থেমে যাবো। তাই না? লুপের আইডিয়াটা ঠিক তাই।

আসলে এককাজ বারবার করতে আমাদের সকলেরই খারাপ লাগে যেমন একই সিল ৫০টা ইনভেলপ এর মধ্যে মারা বা ধরুন একই কথা ১০০টা পেজের মধ্যে লেখা ইত্যাদি।প্রোগ্রামিং এ মজার ব্যাপারটা হচ্ছে একটু চিন্তা করলেই এইসব পূনরাবৃত্তির কাজ কয়েক লাইন লিখেই করা যায়।লুপ দিয়ে এগুলো করা যায়।
লুপ হচ্ছে এমন একটা statement যেটা দিয়ে একটা কোডের ব্লক কে নির্দিষ্ট কয়েকবার execute করা যায় যতক্ষন না আমাদের কাজটা শেষ হয়।
৪ ধরনের লুপ আছে-

* While Loop  
* Do…while Loop
* For Loop
* Foreach Loop



```php
<?php
while (condition is true) {
  code to be executed;
}
```
### While Loop:

```php
<?php
$x = 1;

while($x <= 5) {
  echo "The number is: $x <br>";
  $x++;
}
```

### Do…while Loop:

```php
<?php
$x = 1;

do {
  echo "The number is: $x <br>";
  $x++;
} while ($x <= 5);

```

### For Loop: 

```php
<?php
for ($x = 0; $x <= 10; $x++) {
  echo "The number is: $x <br>";
}
?>
```

### Foreach loop:

```php
<?php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $value) {
  echo "$value <br>";
}
?>

```

### Function: 
প্রোগ্রামিং এর ভাষায় ফাংশন হলো একটি নির্দিষ্ট ধরনের কাজ করে এমন কতগুলো ইন্সট্রাকশনের সমষ্টি। কোন একটা কাজ একই নিয়মে বার বার করাকে function বলে ।

উদাহরন: ফাংশন একটা মহা মজার জিনিস। ফাংশনের আইডিয়াটা হচ্ছে একটা কালো জাদুর বাক্সের মতো। ধরো আমার একটা সুন্দর জাদুর বাক্স আছে যেটা দিয়ে আমি জাদু দেখাই। আমি যখন সেখানে একটা ব্যাঙকে ভরে ফেলি, তখন একটা রাজপুত্র বের হয়ে আসে। যখন একটা খরগোশ ভরি বাক্সে, তখন একটা প্রজাপতি বের হয়ে আসে। আর একটা পিঁপড়াকে ঢুকায়ে দিলে একটা হাতি বের হয়ে আসে। জানো এই কনসেপ্টটাই হচ্ছে ফাংশন।

``` php
<?php
function writeMsg() {
  echo "Hello world!";
}

writeMsg(); // call the function
?>
```
### কমেন্ট/Comments: 
যখন আপনি কোড লিখছেন তখন হয়তো আপনি কোন জটিল এলগরিদম লিখছেন যেটা কিছুদিন পর আপনি নিজে দেখলে এলিয়েনদের কোড মনে হতে পারে। PHP অথবা যেকোনো Programming Language এ Comments হচ্ছে, একজন কোডার বা প্রোগ্রামারের সোর্স কোডের ব্যাখ্যা বা পাদটীকা। এটাকে আমরা Coding Documentation ও বলতে পারি।

PHP তে Comments মূলত দুই প্রকার :

* Single Line Comments (প্রত্যেক line এর জন্য আলাদা ভাবে comment চিহ্ন ব্যবহার করতে হয় )
 * Multi Line Comments (একসাথে একাধিক লাইনে এর জন্য শুধু একবার কমেন্ট চিহ্ন ব্যবহার করতে হয়।)

### single-line comments:
```html

<!DOCTYPE html>
<html>
<body>

<?php
// This is a single-line comment

</body>
</html>

```
###  Multi Line Comments: 

```html
<!DOCTYPE html>
<html>
<body>

<?php
/*
This is a multiple-lines comment block
that spans over multiple
lines
*/
?>

</body>
</html>
```

# The  Basic Concepts OOP of any Programming Language 

### Object Oriented Programming কি?
Computer Programming এ class এবং Object এর ধারণাকে কাজে লাগিয়ে যে Programming করা হয় তাকেই বলা হয় Object Oriented Programming। যে প্রকার প্রোগ্রামিং এ অনেক অনেক অবজেক্ট কে নিয়ে বা অবজেক্ট কে ঘিরে প্রোগ্রামিং করা হয় তাকে OOP বা অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং বলে।

### Object: 
আমরা আমাদের চার পাশে যা কিছু দেখি তার সবই Object বা বস্তু। এই ধরুন আপনি আপনার নিজেকে এবং আপনার আসে-পাশের দিকে খেয়াল করুন , আপনার গায়ের জামা, আপনার পরনের প্যান্ট, হাতের মোবাইল, পড়ার টেবিল,বসার চেয়ার ,কম্পিউটার এই সবই একেকটি Object বা বস্তু। এমনকি আপনি / আমি নিজেও একটা Object.

``` php
<?php
class Car {
 // properties
  public $comp;
  public $color = 'beige';
  public $hasSunRoof = true;
  
  // method that says hello
  public function hello() 
  {
    return "beep";
  }
}
```

### Class: 
ক্লাস হল এমন একটা বিষয় যেখানে C এর শেষ আর অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং এর শুরু। ক্লাস ছাড়া অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং সম্ভব নয়। কারন প্রতিটা অবজেক্ট একটা ক্লাসের মধ্যে থাকবেই। যেমন, মানুষের ক্লাস কি? হিউম্যান ক্লাস। গরু, ছাগল, বাঘ, ভালুক, সিংহ ইত্যাদি অ্যানিম্যাল ক্লাস এর অন্তর্গত। ঘুঘু, শালিক, ময়না, ছিল,শালিক ইত্যাদি বার্ড ক্লাস এর অন্তর্গত। তার মানে ক্লাস হল একটা জাতি যা নির্ধারণ করবে কোন একই শ্রেণির এক একটা অবজেক্ট এবং তার মেথড কে।

``` php
// Declare the class
<?php
class Car {
  // The code
}
```

``` php
<?php

class user
{
    public $username = 'Subrata';
}

$user = new User;
echo  $user->username;  // Output: Subrata
```

### $this keyword: 
OOP তে $this একটি বিশেষ ভ্যারিয়েবল। এটি একই অবজেক্টকে নির্দেশ করে। $this কীওয়ার্ড ব্যবহার করে আপনি একটি ক্লাসের প্রোপার্টি এবং মেথডসমুহকে ঐ ক্লাসের মধ্য থেকেই অ্যাক্সেস করতে পারবেন।
```php
<?php
 class Greeting{

   public $guestName;
   public function welcome(){
     echo "Welcome ".$this->guestName."<br>";
    	 }
 }

?>
```

### public vs. private: 

একটি ক্লাসের অন্তর্গত প্রোপার্টি এবং মেথডসমুহ ক্লাসের বাইরে থেকে অ্যাক্সেস করার অনুমতি আছে কিনা তা নির্ধারন করার জন্য অ্যাক্সেস মডিফায়ার ব্যবহার করা হয়। এটি অতিব প্রয়োজনীয়। কারন, আপনার প্রোগ্রামের তথ্য কোডসমুহ কে/কারা অ্যাক্সেস করতে পারবে তা আপনাকেই নির্ধারন করে দিতে হবে।<br>

অ্যাক্সেস মডিফায়ার তিন ধরনের হয়। যথাঃ

* public
* private
* protected

### public অ্যাক্সেস মডিফায়ার:
যে সকল প্রোপার্টি এবং মেথডের পূর্বে public কীওয়ার্ড ব্যবহার করবো ঐ সকল প্রোপার্টি এবং মেথড সমুহকে ক্লাসের বাইরে থেকে যে কেউ অ্যাক্সেস করতে পারবে। নিম্নের উদাহরণটি লক্ষ্য করলেই বুঝতে পারবেনঃ

``` php
 class Greeting{

   public $name;
   public function hello(){
      echo "Hello ". $this->name.".";
    	  }
 }
//নতুন অবজেক্ট তৈরি করা
 $greeting = new Greeting();
 // name প্রোপার্টিকে ক্লাসের বাইরে থেকে অ্যাক্সেস করা হয়েছে।
 $greeting->name = "Tamjid";
 //hello() মেথডকে ক্লাসের বাইরে থেকে অ্যাক্সেস করা হয়েছে।
 $greeting->hello();

```

উপরের উদাহরণে $name প্রোপার্টি এবং hello() মেথড এর পূর্বে public কীওয়ার্ড ব্যবহারের ফলে এগুলোকে ক্লাসের বাইরে থেকে অ্যাক্সেস করা সম্ভব হয়েছে।

### private অ্যাক্সেস মডিফায়ার:
আমরা একটি ক্লাসের অন্তর্গত প্রোপার্টি এবং মেথডসমূহকে ক্লাসের বাইরে থেকে অ্যাক্সেস রোধ করতে পারি। এটি করার জন্য আমরা প্রোপার্টি এবং মেথড ঘোষণা করার সময় public কীওয়ার্ডের পরিবর্তে private কীওয়ার্ড ব্যবহার করবো।

নিম্নের উদাহরণে আমরা $name ভ্যারিয়েবলে public কীওয়ার্ড এর পরিবর্তে private কীওয়ার্ড ব্যবহার করেছিঃ


```php
 class Greeting{

   private $name;
   public function hello(){
      echo "Hello ". $this->name.".";
    	  }
 }

 $greeting = new Greeting();
 $greeting->name = "Tamjid";
 $greeting->hello();

```
$name প্রোপার্টির অ্যাক্সেস মডিফায়ার private হওয়ায় এটিকে আর ক্লাসের বাইরে থেকে অ্যাক্সেস করা সম্ভব না। এটি করার কারণেই একটি error পাওয়া গেছে।


### Constructor:
পিএইচপির বিশেষ ধরণের বিল্ট-ইন মেথড। অবজেক্ট তৈরির সময় প্রোপার্টির ভ্যালু এসাইনে সম্মতি দেয়। অবজেক্ট তৈরি হলে এই মেথডটি স্বয়ংক্রিয়ভাবেই সম্পাদিত হয়। দুটি আন্ডারস্কোর(__) দিয়ে construct মেথড শুরু হয়।
``` php
<?php
class Fruit {
  public $name;
  public $color;

  function __construct($name) {
    $this->name = $name;
  }
  function get_name() {
    return $this->name;
  }
}

$apple = new Fruit("Apple");
echo $apple->get_name();
?>
``` 
### Inheritance/ বংশ পরিক্রমা:
Inheritance মানে হল বংশ পরিক্রমা। আপনি আপনার বাবার থেকে এসেছেন। আপনার বাবা আপনার দাদার থেকে এসেছেন। এটাই হল inheritance. যেমনঃ এটি প্রোগ্রামিং প্যারাডাইমের একটি সুত্রাত্মক উদাহরণ যা ওপরের উদাহরণে বর্ণিত হয়েছে। এই উদাহরণে, Dog ক্লাসটি Animal ক্লাস থেকে বংশ পরিক্রমা করে এবং এটি তার পিতা ক্লাসের বৈশিষ্ট্য, মেথড, ইত্যাদি উপলব্ধি করে। বংশ পরিক্রমার মাধ্যমে, কোড পুনরাবৃত্তি কম হয়, একটি ক্লাসের ফিচার পুনরাবৃত্তি করা যায়, এবং কোড ব্যবস্থাপনা সহজ হয়ে থাকে।

``` php
<?php

// Parent class
class Animal {
    protected $name;
    protected $color;

    public function __construct($name, $color) {
        $this->name = $name;
        $this->color = $color;
    }

    public function speak() {
        echo "Animal speaks\n";
    }

    public function displayDetails() {
        echo "Name: {$this->name}, Color: {$this->color}\n";
    }
}

// Child class inheriting from Animal
class Dog extends Animal {
    private $breed;

    public function __construct($name, $color, $breed) {
        parent::__construct($name, $color);
        $this->breed = $breed;
    }

    public function speak() {
        echo "Dog barks\n";
    }

    public function displayDetails() {
        parent::displayDetails();
        echo "Breed: {$this->breed}\n";
    }
}

// Creating objects
$animal = new Animal("Unknown", "Unknown");
$dog = new Dog("Max", "Brown", "Labrador");

// Calling methods
$animal->speak(); // Output: Animal speaks
$animal->displayDetails(); // Output: Name: Unknown, Color: Unknown

$dog->speak(); // Output: Dog barks
$dog->displayDetails(); // Output: Name: Max, Color: Brown, Breed: Labrador


``` 

### Getters and setter: 
Getters এবং setters হল একটি ক্লাসের অ্যাট্রিবিউট (বা বৈশিষ্ট্য) অ্যাক্সেস নিয়ন্ত্রণ করার জন্য পিএইচপি-র মতো অবজেক্ট-ওরিয়েন্টেড প্রোগ্রামিং ভাষায় ব্যবহৃত পদ্ধতি। তারা ব্যক্তিগত বা সুরক্ষিত বৈশিষ্ট্যের মানগুলি পড়ার (পাওয়া) এবং সংশোধন (সেট) করার একটি উপায় প্রদান করে, একটি বস্তুর মধ্যে ডেটা এনক্যাপসুলেট করে এবং এটিতে নিয়ন্ত্রিত অ্যাক্সেস প্রদান করে।

```php
<?php

class user{

    public $email;


    public function setEmail($email) //setter
    {
        if(filter_var($email,  FILTER_VALIDATE_EMAIL)){
            return;
        }
        $this->email = $email;
    }

    public function getEmail() //getter
    {
        return strtolower($this->email);
    }

}

$user = new user;
$user->setEmail('hello@subrata.me');
echo $user->getEmail(); // Output: hello@subrata.me

```


#### Getters:
``` php
<?php
class MyClass {
    private $value;

    public function getValue() {
        return $this->value;
    }
}
```

#### setter:
```php
<?php
class MyClass {
    private $value;

    public function setValue($newValue) {
        $this->value = $newValue;
    }
}

```

### Encapsulation:
উত্তরাধিকার সূত্রে কোনো কিছু পাওয়াকে ইনহেরিটেন্স বলে। OOP বা অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং এ একটি প্রধান ক্লাস এর কিছু প্রোপার্টি নিয়ে নতুন এক বা একাধিক ক্লাস বানানো কে ইনহেরিটেন্স বলে।

Encapsulation হল অবজেক্ট এবং মেথড কে একটা capsul এর মধ্যে আবদ্ধ রাখা। অর্থাৎ অবজেক্ট এবং ক্লাস কখনো আলাদা থাকতে পারে না। যেমন ধরুনঃ আপনি বাজারে গিয়ে ৫ কেজি চাল কিনলেন। দোকানদার আপনাকে কিভাবে চাল দিবে? অবশ্যই একটা ব্যাগ এ তাই না? ধরুন ব্যাগ টা হল অবজেক্ট আর চাল হল মেথড। এখন আপনি যেখানে যাবেন ব্যাগ এ করেই আপনাকে চাল নিয়ে যেতে হবে। আবার ধরুন আপনি ভাল গান গাইতে পারেন। আপনি যেখানেই যান, আপনি গান গাইতে পারবেন। তাই না? মানে গান আপনার থেকে কোনোভাবে আলাদা করা সম্ভব নয়। সহজ ভাষায় এটাই হল Encapsulation. তাছাড়া আমরা আগেও দেখেছি যে object.method=instance. মানে instance create করার শর্তই হল object এবং method কে capsul এর মধ্যে রাখা এবং এদের একটি ডট দিয়ে encapsulate করে রাখা হয়।

Encapsulation করার আরেকটি গুণ হল ডাটা হাইড করে রাখা যায়। অর্থাৎ ২ টা সেমিকোলনের ভিতরে মেথড create করলে একটা মেথড অন্য মেথড এর variable কে access করতে পারবে না। ফলে এক মেথডের ডাটা অন্য মেথডের কাছে সুরক্ষিত থাকে। Data Hiding Encapsulation এর একটি বড়ো বৈশিষ্ট্য।

``` 
class child_class_name extends parent_class_name {
    use trait_name;
    ...
    ...
    child_class functions
}
```


```
<?php

class validator
{
   protected $errors =[];


   public function validator ($data, $rules) 
    {
        // 
         $this ->errors[] = 'The email is required';     
     }

   public function fails()
   {
        return !empty($this->errors);

   }  

   public function geterrors()
   {
    return $this->errors;
   }


}


$validator =new  validator;
$validator ->validator(['email'=>'example@gmail.com'],['required']);


if($validator ->fails()){
   die('Fails');    
}
else{
   echo "Success";
}

```


``` 
<?php
// Class Geeks 
class Geeks { 
  public function sayhello() { 
     echo "Hello"; 
  } 
} 
  
// Trait forGeeks 
trait forGeeks { 
  public function sayfor() { 
     echo " Geeks"; 
  } 
} 
  
class Sample extends Geeks { 
   use forGeeks; 
   public function geeksforgeeks() { 
      echo "\nGeeksforGeeks"; 
  }  
} 
  
$test = new Sample(); 
$test->sayhello(); 
$test->sayfor(); 
$test->geeksforgeeks(); 

```  

### Polymorphism:
Poly অর্থ বহু। Morph অর্থ ফর্ম। তার মানে Polymorphism মানে হল ফর্মের বহুরূপতা। Polymorphism মানে বহুরূপিতা। অর্থাৎ একটা অবজেক্ট নানা সময় নানা রকম রূপ ধারণ করতে পারার ব্যাপারটিই হল Polymorphism.

এটা কেমন ফর্ম? এটা অবশ্যই windows form না। এটা হল আপনার অবস্থা বা state।

আপনি ভাল গান গাইতে পারেন। আপনার বাবার থেকে inherit হয়ে এই বৈশিষ্ট্য আপনার মাঝে এসেছে। কিন্তু আপনি আপনার বাবার থেকে ভাল গান করতে পারেন। এটাই হল polymorphism. আবার আপনার বাবার অনেক রাগ। কিন্তু আপনি সহজে রাগেন না। এটাও polymorphism. polymorphism positive এবং negative ২ ই হতে পারে। আপনি একটা windows form নিয়ে নানাভাবে ডিজাইন করতে পারেন। এটা হল আপনার windows এর বহুরূপতা।

```php
class Circle implements Shape {
  private $radius;
   
  public function __construct($radius)
  {
    $this -> radius = $radius;
  }
  
  // calcArea calculates the area of circles 
  public function calcArea()
  {
    return $this -> radius * $this -> radius * pi();
  }
}
```  
### Namespace:
Namespace কি? এটা বুঝার জন্য আপনাদেরকে একটা গল্প বলব। মামনুন এবং মুহিব দুই ভাই , তাদের একজনের বয়স ৪ বছর অপরজনের বয়স ৩ বছর। তাদেরকে দেখতে একই রকমের খেলনা দিতে হয় । আর দেখতে হুবহু একই রকম না দিলে কোনটা বেশি সুন্দর বা কোনটা কম সুন্দর তা নিয়ে তারা সারাক্ষন ঝগড়া করে। আর তাই তাদের বাবা সবসময় হুবহু একই রকমের ২ টি খেলনা ই কেনেন। এদিকে একই রকম হওয়ায় তাদের বাবা আরেকটা সমস্যায় পড়লেন, একজন আরেকজনের খেলনা নিয়ে কাড়াকাড়ি করে আর জগড়া করে, কারণ কে কার খেলনা ববহার করছে বুঝতে পারে না। এই সমস্যা সমাধানের জন্য তাদের বাবা তাদের প্রত্যেকের খেলনায় একটি করে লেভেল লাগিয়ে দেয় । যেন প্রত্যেকে তার নিজেরটা চিনে নিতে পারে। এখন আর সমস্যা হয় না । বলা যায় Namespace এক ধরনের লেভেল বা স্টিকার। আবার বলা যায়, PHP তে Namespace ধারণা অনেকটা আমাদের কাছে একইনামের দুটি file কে দুটি ভিন্ন ফোল্ডারে রাখার মতো। অর্থাৎ, foo/info.txt এবং bar/info.txt path এর মতো। যদিও বাস্তবে namespace declare করার জন্য আমাদেরকে এইরকম folder তৈরী এর পরিবর্তে একটা ভার্চুয়াল path দিয়ে access করতে হবে।

```php 
<?php
namespace namespaceName;
/*
Your PHP Code Goes hear
*/
```  
### কিভাবে namespace সহ constant, function এবং class কে কল করবেন?

namespace সহ constant, function এবং class কে call ভালো ভাবে বুঝার জন্য প্রথমে আমরা একই নামের constant, function এবং class দিয়ে দুটি ভিন্ন file তৈরী করব দুটি ভিন্ন namespace দিয়ে।

* File: myproject1.php

```php

<?php
// define this code in the MyProject1 namespace
namespace MyProject1;
const a="America";
function test(){
    echo "Hello I'm From MyProject1 Namespace";
}
class Test{
    public $b="Bangladesh";
    public function sayHello(){
        echo "Hello Bangladesh! From MyProject1 Namespace<br>";
    }
}

* File: myproject2.php

```php

<?php
// define this code in the MyProject2 namespace
namespace MyProject2;
const a="Africa";
function test(){
    echo "Hello I'm From MyProject2 Namespace";
}
class Test{
    public $b="Bharma";
    public function sayHello(){
        echo "Hello Bharma! From MyProject2 Namespace<br>";
    }
}
```

এখন আমরা myproject1.php এবং myproject2.php file দুটিকে project.php ফাইল এ include করব। এবং namespace সহ call করব।

* File: project.php

```php
<?php
include("myproject1.php");
include("myproject2.php");
 
 
echo "<h2>Namespace MyProject1</h2>";
echo MyProject1\a,"<br>";
echo MyProject1\test(),"<br>";
$obj=new MyProject1\Test;
echo $obj->b,"<br>";
$obj->sayHello();
 
 
echo "<h2>Namespace MyProject2</h2>";
echo MyProject2\a,"<br>";
echo MyProject2\test(),"<br>";
$obj=new MyProject2\Test;
echo $obj->b,"<br>";
$obj->sayHello();

```

### Namespace এর ব্যবহারের ভিত্তিতে Namespace name তিন প্রকার :

* Unqualified Namespace
* Qualified Namespace
* Fully Qualified Namespace


### Trait: 
সাধারণত PHP কে বলা হয় Single Inheritance Language অর্থাৎ, PHP Language টি Multiple Inheritance সাপোর্ট করেনা। আর Trait হচ্ছে PHP OOP তে Single Inheritance এর সীমাবদ্ধতা দূর করার এবং Multiple Inheritance ব্যবহার করার একটি নতুন concept . যা PHP 5.4 এ প্রথম ব্যবহার করা হয়। Traits অনেকটা class এর মতোই, Trait কে Define করা হয় ক্লাসের মত করেই trait কিওয়ার্ডটি ব্যবহার করে। তবে এর থেকে class এর মত object তৈরী করা যায়না। কিন্তু একাধিক trait এর property এবং Method গুলোকে একটি single class এর মধ্যে ব্যবহার করা যায়। এবার চলুন একটা উদাহরণের মাধ্যমে আরো ভালো ভাবে বুঝা যাক :


```php
<?php
trait Foo
 {
    public function sayHello(){
         return "Hello";
    }
    public function sayWorld(){
     return "World";
    }
 }
?>

```

### Debugging /ডিবাগিং: 

এর আক্ষরিক অর্থ পোকা বাছা। প্রোগ্রামে সংঘটিত যাবতীয় ভুল-ত্রুটিসমুহকে বাগ (Bug) বলে। ডিবাগিং (Debug) : প্রোগ্রামে সংঘটিত ভুল-ত্রুটিসমুহ সংশোধন করার প্রক্রিয়াকে ডিবাগিং (Debug) বলে।

### var_dump: 
var_dump() একটি পিএইচপি ফাংশন যা ডিবাগিং উদ্দেশ্যে ব্যবহৃত হয়। এটি এক বা একাধিক ভেরিয়েবল সম্পর্কে তথ্য আউটপুট করে, এর ধরন এবং মান সহ। এটি প্রায়শই বিকাশের সময় ভেরিয়েবল এবং ডেটা স্ট্রাকচার পরিদর্শন করতে তাদের বিষয়বস্তু বুঝতে বা সমস্যাগুলি নির্ণয় করতে ব্যবহৃত হয়।


```php

<?php

$variable = "Hello, world!";
var_dump($variable);     // string(13) "Hello, world

```

# হ্যালো লারাভেল !


| ক্রমিক নম্বর  | ডিরেক্টরি নাম | বর্ণনা  |
|------------|---------------|--------|
|1   |app  | app  |
|2   | bootstrap  |   bootstrap|     
|3  |Config   | Config  | 
|4  |database   | database  | 
|5  |public   | public  | 
|6  |resources   | resources  | 
|7  |routes   | routes  | 
|8  |storage   | storage  | 
|9  |test   | test  | 
|10  |vendor   | vendor  | 
|11  |.env   | .env  | 
|12  |composer.json   | composer.json  | 


### Vendor
ভেন্ডার সাধারণ অর্থ হচ্ছে লেনদেন । সব লারাভেল প্রোজেক্ট এর প্যাকেজ রাখার রুম। আপনার সব পাকেজ আকানে থাকে
```
লারাভেল প্রোজেক্ট এর প্যাকেজ রুম
```

### env
এই ফাইল এর ভিতরে আপনার গোপনীয় পাসওয়ার্ড , এপিআই সেট করবেন , যা আপনাকে অন্যান্য সাইটের সাথে আপনার সাইট কে সমন্বয় করবে।
আপনি কোন কিছু পোস্ট অথবা ডাটা রাখবেন যা আপনাকে ডাটাবেসে রাখতে হবে । এখানে মাইএস কিউ এল এর কথা তুলে ধরি, মাইএস কিউ এল আপনার লারাভেল প্রোজেক্ট এর সাথে সেটআপ করে নিবেন ।
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ডাটাবেস নাম
DB_USERNAME= ইউজার নাম
DB_PASSWORD= যদি সেট ব্যবহার করেন // নাল
PASSWORD=
```

### composer.json
নতুন প্যাকেজ লারাভেল প্রোজেক্ট এ ব্যবহার করতে চাইলে composer.json এ রেজিস্টার করতে হবে ।
নিচের কোড টা লক্ষ্য করুনঃ

```js
// composer.json
"require": {
    "php": ">=5.6.4",
    "algolia/algoliasearch-client-php": "^1.17",
    "laravel/framework": "5.4.*",
    "laravel/scout": "^3.0",
    "laravel/tinker": "~1.0",
    "laravelcollective/html":"^5.2.0"
},
"require-dev": {
    "fzaninotto/faker": "~1.4",
    "mockery/mockery": "0.9.*",
    "phpunit/phpunit": "~5.7"
          },
```

### থিম / ফ্রন্ট এণ্ড সেটআপ
আমরা যেকোনো সাইট ডীভীলোপ করার আগে মনের মতো টেমপ্লেট বা থিম নির্বাচন করি । প্রতিটা থিম এর ফোল্ডার একই css ,js , imges and html

#### Public folder
আপনি পাবলিক এ যা রাখবেন , শুধু কল করলেই পেয়ে যাবেন ।

- [ ] js
- [ ] jquery.js
- [ ] vue.js
- [ ] css
- [ ] main.css
- [ ] login.css
- [ ] images
  - [ ] logo.png
  - [ ] banner.jpg
     

### Resources folder
Resources folder assets , lang , views

এখন Resources views এর গল্প । আপনার সাইট এর ফ্রন্ট এর সকল পি এইচ পি ফাইল এখানে থাকবে । এখানে যে যার ইচ্ছে মত সাজিয়ে গুছিয়ে ফাইল গুলো রাখে ।

একটা সাইট এ header, footer , sidebar এসব সব পেজেই লাগে । আপনি কি এসব বার বার প্রত্যেক পেজে যুক্ত করবেন ? তাতে সময় অপচয় ।
। তাই যেসব কমন , সব পেজে লাগবে, সেসব partials নামে ফোল্ডারে রাখবেন ।

- _head.blade.php
- _aside.blade.php
- _footer.blade.php
- _mystyle.blade.php
- _scripts.blade.php


এখন এসব ফাইল @include দিয়ে এড করতে হয় । নিচের কোড তা দেখে নিন -

main.blade.php
```
<!DOCTYPE html>
<html>
<head>
  @include('partials\_head')
  @include('partials\_mystyle')
</head>
<body class="framed main-scrollable">
  <div class="wrapper">
      @include('partials\_nav')
      <div class="dashboard">
        @include('partials\_aside')
          <div class="main">
            @yield('maintheme')
          </div>
      </div>
  </div>
    @include('partials\_footer')
      @include('partials\_scripts')
</html>
```
কোডে _mystyle , _scripts এসব আছে । আপনার সব ফাইল _mystyle , ফাইল _scripts এ রাখবেন । আর একটা জিনিস আপনি দেখে হইত ভাবছেন @yield টা কি । কোড তা দেখেন @yield(‘maintheme’) তার মানে হচ্ছে সব পেজে আমরা শুধু main ক্লাস টা পরিবরতন করব । পরিবর্তন করার জন্য @yield ব্যবহার করা হয়ে থাকে ।

_head.blade.php

<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Laravel Blog @yield('title')</title>

title টা সব সময় আলাদা আলাদা করবেন , সেজন্য এখানেও @yield() ব্যবহার করবেন ।

_mystyle.blade.php
 ```
<link href="css/demo.css" rel="stylesheet">
<link rel="stylesheet" href="css/custom.css">
@yield('styleme')
```

সব কাজের শেষে আপনি একটা ফ্রেম ফাইল বানিয়েছেন main.blade.php । এই ফাইল টা আপনার সব পেজ এ @extends(‘main’) করবেন , তাহলে আপনার main ফাইল সব পেজ পেয়ে যাবে । এখন @yield() নিয়ে কিছু কথা –

```
@section('styleme')
  <link rel="stylesheet" href="js/datatable/dataTables.bootstrap.css">
  <link rel="stylesheet" href="js/datatable/dark.css">
@endsection
```

### Extending A Layout

```
@extends('layouts.app')
@section('title', 'Page Title')
@section('sidebar')
    @parent
    <p>This is appended to the master sidebar.</p>
@endsection
@section('content')
    <p>This is my body content.</p>
@endsection

````

থিমের কাজ আপনার কমপ্লিট ।


### Condition / Resource

Condition - শর্ত । Condition ছাড়া আমরা কিছুই করি না । কোন শর্তে আপনি লারাভেল শিখছেন , হইত লারাভেল জনপ্রিয় তাই , বা ইনকাম ভাল বা আপনি শিখার আগ্রহ , যাই হক শর্ত একটা আছে । আপনি Condition সম্পর্কে জানেন , আকানে বিস্তারিত বলার কিছু নাই , না জেনে থাকলে শিখে নিবেন ।

@if , @else

```
@if (count($records) === 1)
    I have one record!
@elseif (count($records) > 1)
    I have multiple records!
@else
    I don't have any records!
@endif
```

@unless
```
@unless (Auth::check())
    You are not signed in.
@endunless
```


@isset , @empty

```
@isset($records)
    // $records is defined and is not null...
@endisset
@empty($records)
    // $records is "empty"...
@endempty
```
### Loop Master

আপনি অবশ্যই লুপের সাথে পরিচিত । সহজ ভাষাতে একই কাজ বার বার একই ভাবে করা হচ্ছে Loop । এখানে
```
@for ($i = 0; $i < 10; $i++)
    The current value is {{ $i }}
@endfor
@foreach ($users as $user)
    <p>This is user {{ $user->id }}</p>
@endforeach
@forelse ($users as $user)
    <li>{{ $user->name }}</li>
@empty
    <p>No users</p>
@endforelse
@while (true)
    <p>I'm looping forever.</p>
@endwhile
```

আপনি লুপ শেষ / স্কিপ করতে চান – @break, @continue ,

```
@foreach ($users as $user)
    @if ($user->type == 1)
        @continue
    @endif
    <li>{{ $user->name }}</li>
    @if ($user->number == 5)
        @break
    @endif
@endforeach
```


আপনি এভাবে ও একই ফলাফল পাবেন । যেকোনটা ফলো করতে পারেন ।

```
@foreach ($users as $user)
    @continue($user->type == 1)
    <li>{{ $user->name }}</li>
    @break($user->number == 5)
@endforeach

```


### ডাটাবেস আলাপ - (Database)
সবাই কম বেশি ডাটা কথাটা শুনেছেন । ডাটা মানেই সেখানে কিছু তথ্যের কারবার । ডাটাবেস টা হচ্ছে আপনার যাবতীয় তথ্য সংগ্রহশালা । অন্য ভাবে বললে ডাটাবেস হচ্ছে schemas, tables, queries, reports এসবের কালেকশন ।

#### কোন ডাটাবেস ব্যবহার করবো ?
লারাভেল চারটা ডাটাবেস কে পরিচয় করিয়ে দিয়েছে

MySQL
Postgres
SQLite
SQL Server
আপনি যে ডাটাবেস ভাল লাগে সেটা ব্যবহার করতে পারেন । আপনি লারাভেল প্রোজেক্ট এর ডাটাবেস কনফিগারেশন পাবেন config/database.php তে ।

### ডাটাবেস সেটআপ পদ্ধতিঃ

SQLite কনফিগারেশন -
SQLite সেটআপ করতে আপনাকে প্রথমে কম্যান্ড করতে হবে touch database/hello_laravel.sqlite । তাহলে আপনার

database ফোল্ডার এ hello_laravel.sqlite নামে একটা ফাইল দেখতে পাবেন । এই ফাইল টা আপনার sqlite এ যুক্ত করতে হবে ।

এখন লারাভেল প্রোজেক্ট এর DB_CONNECTION এ দেন sqlite , DB_DATABASE এ database/hello_laravel.sqlite

```
DB_CONNECTION=sqlite
DB_DATABASE=database/hello_laravel.sqlite
```


### ডাইনামিক ডাটা টেবিল তৈরি / মাইগ্রেশন

মাইগ্রেশন এর জন্য টার্মিনাল গিয়ে হিট করুন ।

```
php artisan make:migration create_posts_table --create=posts


###এখন

-database
  -migrations
    -2017_02_06_175142_create_posts_table.php

গিয়ে এ এমন একটা ফাইল পাবেন । আপনি ডাটা কি কি রাখবেন সেটা সেট আপ দিবেন।

```
 <?php
use Illuminate\Database\Schema\Blueprint;
use Illuminate\Database\Migrations\Migration;
class CreatePostsTable extends Migration
{
    /**
     * Run the migrations.
     *
     * @return void
     */
    public function up()
    {
        Schema::create('posts', function (Blueprint $table) {
            $table->increments('id');
            $table->string('title');
            $table->text('body');
            $table->timestamps();
        });
    }
    /**
     * Reverse the migrations.
     *
     * @return void
     */
    public function down()
    {
        Schema::drop('posts');
    }
}
```

মাইগ্রেশন এ দুইটা মেথড থাকে up এবং down

এখন ডাটাবেস এ কমান্ড এর মাধ্যমে টেবিল এড করার পালা , টার্মিনাল এ হিট করুন

```
php artisan migrate

```


কোন এরর না আসলে আপনি সফলভাবে টেবিল যুক্ত করতে পারছেন । আপনার প্যানেল এ যাচাই করুন users নামে টেবিল যুক্ত হয়েছে এবং তথ্য গুলো সব আছে ।

### নতুন কলাম যুক্ত করা
আপনার নামে একটা টেবিল আছে , এখন আপনি ওই টেবিল আরও কিছু তথ্য যুক্ত করতে চাচ্ছেন , তাহলে টার্মিনালে হিট করুন

```
php artisan make:migration add_category_id_to_posts --table=posts
```

category_id যুক্ত হবে posts টেবিলে ।

```
<?php
use Illuminate\Database\Schema\Blueprint;
use Illuminate\Database\Migrations\Migration;
class AddCategoryIdToPosts extends Migration
{
    /**
     * Run the migrations.
     *
     * @return void
     */
    public function up()
    {
        Schema::table('posts', function (Blueprint $table) {
            $table->integer('category_id')->nullable()->after('slug')->unsigned();
        });
    }
    /**
     * Reverse the migrations.
     *
     * @return void
     */
    public function down()
    {
        Schema::table('posts', function (Blueprint $table) {
            $table->dropColumn('category_id');
        });
    }
}

```

এখন ডাটাবেস এ কমান্ড এর মাধ্যমে আগের টেবিল এ নতুন কলাম এড করার পালা , টার্মিনাল এ হিট করুন

```
php artisan migrate
```

ডাটাবেস যাচাই করুন slug পরে category_id কলাম যুক্ত হয়েছে

উপরের কোডটি অপরিহার্য এবং পুনরাবৃত্তিমূলক। এটি একটি গণিত সম্পত্তি সংস্করণের সাথে তুলনা করুন:

```
var vm = new Vue({
  el: '#demo',
  data: {
    firstName: 'Foo',
    lastName: 'Bar'
  },
  computed: {
    fullName: function () {
      return this.firstName + ' ' + this.lastName
    }
  }
})
```
অনেক ভালো, তাই না?

### কলাম টাইপ

```
Command	Command	Command
$table->bigIncrements('id');	$table->bigInteger('votes');	$table->binary('data');
$table->boolean('confirmed');	$table->char('name', 4);	$table->date('created_at');

```

### Query Builder

#### database tips:
```
$users = DB::table('users')->get();

$users = App\User::all(); / $users = User::all();
```
### Retrieving Results

Retrieving All Rows From A Table

ডাটাবেসের সকল সারির ডাটার জন্য নিচের কোড অনুসরন করতে হবে । $users = DB::table(‘users’)->get(); $users একটা ভারিয়েবল , DB::table(‘users’) এর users ডাটাবেস টেবিল নাম । DB:: হচ্ছে লারাভেল এর facade । DB:: , UserController এ ব্যবহার করার জন্য use Illuminate\Support\Facades\DB; প্রথমে বলে দিতে হবে । get(); [] মেথড দিয়ে সব ডাটা পাবেন ।

```
 <?php
namespace App\Http\Controllers;
use Illuminate\Support\Facades\DB;
use App\Http\Controllers\Controller;
use DB;
class UserController extends Controller
{
    /**
     * Show a list of all of the application's users.
     *
     * @return Response
     */
    public function index()
    {
        $users = DB::table('users')->get();
        return view('user.index', ['users' => $users]);
    }
}
```

মডেল এর মাধ্যমে ডাটা সংগ্রহঃ
```
<?php
namespace App\Http\Controllers;
use Illuminate\Support\Facades\DB;
use App\Http\Controllers\Controller;
use App\User;
class UserController extends Controller
{
   /**
    * Show a list of all of the application's users.
    *
    * @return Response
    */
   public function index()
   {
       $users = User::all();
       return view('user.index', ['users' => $users]);
   }
}
```
### Chunking Results

### Aggregates

### Selects
সব সময় ডাটা টেবিল এর সকল কলাম এর দরকার পরে না । যে যে কলাম দেখাতে চান সেগুলো select() মেথড দিয়ে ফিক্স ট করে দিতে হবে । যেমনঃ সকল user এর name এবং email

```
$users = DB::table('users')->select('name', 'email')->get();
```
distinct - (স্বতন্ত্র) ব্যবহার করলে কোন মাল্টিপল একই ডাটা একটা ডাটা হিসেবে শো করবে । যেমনঃ users এর দেশ এর লিস্ট $users->country । users দের দেশ বাংলাদেশ যতবার এ থাকুক সেটা একবার ই দেখাবে ।

```
$users = DB::table('users')->distinct()->get();
```

### joins
একটা টেবিল কে অন্য টেবিল এর সাথে সংযুক্ত করার জন্য join() ব্যবহার করতে পারেন ।Inner Join ,Left Join , right Join সবগুলোর কাজ একই । Inner Join এর মাধ্যমে users টেবিল এর সাথে contacts , orders টেবিল সংযুক্ত । এই কাজ তা আপনি চাইলে ফরেন কে দিয়েও করতে পারেন ।
```
$users = DB::table('users')
            ->join('contacts', 'users.id', '=', 'contacts.user_id')
            ->join('orders', 'users.id', '=', 'orders.user_id')
            ->select('users.*', 'contacts.phone', 'orders.price')
            ->get();

  ```
  ### where package
  Where সম্পর্কে একটা গল্প বলি । সামিনা আর রুবি দুই বান্ধবী । বন্ধু বান্ধব রা তো আড্ডা চলে । একদিন আড্ডার ফাকে সামিনা রুবি কে বলতাছে দোস্ত ঢাকাতে তুই অনেকদিন যাবত আছিস , ঢাকার ভিতথা ঐতিহাসিক কোথায় গেছিস । রুবি বলল লালবাগ কেল্লা , আহসান মঞ্জিল , পানাম নগর । রুবি কিন্তু মহাস্থানগড় বা ঢাকার বাইরের জায়গার নাম বলে নি , কারন সামিনা বলেছে ঢাকার ভিতরের জায়গা ।

Where এ কিছু শর্ত দিয়ে দেওয়া হয় , ফলাফল শর্ত মেনে চলে । Where এ তিনটি আর্গুমেন্ট থাকে কলামের নাম , অপারেটর (=, <=,>=) , ভ্যালু

যে যে user এর votes সংখ্যা ১০০ এর সমান , শুধু সেসব user এর ডাটা দেখাবে ।

```
$users = DB::table('users')->where('votes', '=', 100)->get();
```
যদি কোন অপারেটর ব্যবহার না করেন , সেটা অটোমেটিক সমান (=) অপারেটর হয়ে যাবে ।


```
$users = DB::table('users')->where('votes', 100)->get();
```
Where Array : দুই বা ততোধিক কলাম Where এ ব্যবহার করতে চাইলে অ্যারে করতে হবে । এসময় Where ,And (&& ) এর মত কাজ করবে
```
$users = DB::table('users')->where([
    ['status', '=', '1'],
    ['subscribed', '>', '100'],
])->get();
```

### orWhere:
যেকোনো শর্ত মেনে চললে ফলাফল দেখাবে ।

```
$users = DB::table('users')
                    ->where('votes', '>', 100)
                    ->orWhere('name', 'John')
                    ->get();
```
### whereBetween
যেখানে user এর vote 100-500 , সেসব user এর ডাটা দেখাবে ।

```
$users = DB::table('users')
                  ->whereBetween('votes', [100, 500])->get();
```

### whereNotBetween
whereNotBetween হচ্ছে whereBetween এর উল্টা । যেখানে user এর vote 100-500 , সেসব user এর ডাটা ছাড়া বাকি সব user এর ডাটা দেখাবে ।

```
$users = DB::table('users')
                    ->whereNotBetween('votes', [100, 500])
                    ->get();
 ```

 ### Ordering, Grouping, Limit, & Offset

### orderBy
orderBy এ দুইটা টপিক ascending (asc), descending (desc) । এই টপিক এ খুব মনে পরবে ক্লাস ওয়ান এর ছোট হতে বড় , বড় হতে ছোট ক্রমিক সংখ্যা সাজানো । ascending হচ্ছে ছোট হতে বড় সাজানো আর descending হচ্ছে বড় হতে ছোট সাজানো । asc করলে চলে আবার না করলেও চলে , অটোমেটিক সব asc আকারে দেখাবে । অনেক সময় descending আকারে সাজানোর প্রয়োজন হয় , যেমন কোন সাইট এর এডমিন যদি সকল পোস্ট দেখতে চান , তখন পোস্তগুলোকে desc এ সাজাতে হয় ।

```
$users = DB::table('users')
                ->orderBy('name', 'desc')
                ->get();
```

### latest / oldest

```
$user = DB::table('users')
                ->latest()
                ->first();
 ```
### skip / take

```
$users = DB::table('users')->skip(10)->take(5)->get();
```

### offset / limit

```
$users = DB::table('users')
                ->offset(10)
                ->limit(5)
                ->get();
 ```

### update()

```
DB::table('users')
            ->where('id', 1)
            ->update(['votes' => 1]);
```
### Increment & Decrement

```
DB::table('users')->increment('votes');
DB::table('users')->increment('votes', 5);
DB::table('users')->decrement('votes');
DB::table('users')->decrement('votes', 5);
```
### Deletes

```
DB::table('users')->delete();
DB::table('users')->where('votes', '>', 100)->delete();

```

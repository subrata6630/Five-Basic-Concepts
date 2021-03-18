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

```
    Intiger  (ইন্টিজার)

    Float / Double (ফ্লট বা ডাবল)

    Boolean  (বুলিয়ান)

    String (স্ট্রিং)

    Array (এরে)

    Object (অবজেক্ট)

```



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
?>
```

### Loop (লুপ):

লুপ বা রিপিটেশন মানে হচ্ছে একই কাজ বারবার করা। লুপ এর কথা মাথায় আসলেই আমরা একটা বৃত্তের কথা চিন্তা করি, অথবা ইনফিনিটি সাইনের কথা চিন্তা করি। প্রোগ্রামিং এর লুপ হচ্ছে একই কাজ বার বার না করে একবার কাজটা করে যতবার খুশি ততবার রিপিট করার একটা মাধ্যম।

লুপ হচ্ছে এমন একটি কমান্ড যার সাহায্যে একটি কাজ অনেক বার করা যায়। লুপিং এর কাজে সবছেয়ে বেশি ব্যবহৃত হয় for loop. এ for loop এর তিনটি অংশ রয়েছে। তার আগে আমরা দেখেনি for loop সাধারন ব্যবহার নিয়ম।

উদাহরন: প্রোগ্রামিং এর সবচে' অসাধারণ ব্যাপার হচ্ছে কি, যদি তোমার একই কাজ বার বার করতে হয়, সেটা তুমি লুপে ফেলে করে ফেলতে পারো। ধরো, হুকুশ পাকুশ একদিন ভুলে গেলো ক্লাসে হোমওয়ার্ক করে নিতে। তখন ম্যাডাম ওকে বললো, তোমাকে এক হাজার বার লিখে আনতে হবে যে তুমি প্রতিদিন হোমওয়ার্ক করবে। হুকুশ পাকুশ ভাবলো সে যদি একটা লাইন লিখে সেটাকে বারবার করে কপি করে, তাহলেও গুনে গুনে এক হাজার বার কপি করতে হবে। কত্ত ঝামেলা, তাই না?

এবার চিন্তা করো, এটা আমরা হাতে হাতে কিভাবে করতাম? ধরো আমি শীতের ছুটি কাটাতে যাবো দাদুবাড়িতে - আমাকে দশটা জামা নিতে হবে কারণ আমি পুরো মাসটা সেখানে থাকবো। আমি করবো কি একটা একটা করে জামা নিবো, আর হাতে গুনবো আমি কয়টা জামা নিয়েছি। যখন দেখবো আমার হাতের আঙ্গুল গোনায় দশটা হয়ে গেছে তখন আমি থেমে যাবো। তাই না? লুপের আইডিয়াটা ঠিক তাই।

আসলে এককাজ বারবার করতে আমাদের সকলেরই খারাপ লাগে যেমন একই সিল ৫০টা ইনভেলপ এর মধ্যে মারা বা ধরুন একই কথা ১০০টা পেজের মধ্যে লেখা ইত্যাদি।প্রোগ্রামিং এ মজার ব্যাপারটা হচ্ছে একটু চিন্তা করলেই এইসব পূনরাবৃত্তির কাজ কয়েক লাইন লিখেই করা যায়।লুপ দিয়ে এগুলো করা যায়।
লুপ হচ্ছে এমন একটা statement যেটা দিয়ে একটা কোডের ব্লক কে নির্দিষ্ট কয়েকবার execute করা যায় যতক্ষন না আমাদের কাজটা শেষ হয়।
৪ ধরনের লুপ আছে-

```
While Loop

Do…while Loop

For Loop

Foreach Loop

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
### কমেন্ট: 
যখন আপনি কোড লিখছেন তখন হয়তো আপনি কোন জটিল এলগরিদম লিখছেন যেটা কিছুদিন পর আপনি নিজে দেখলে এলিয়েনদের কোড মনে হতে পারে।

### Object Oriented Programming কি?
Computer Programming এ class এবং Object এর ধারণাকে কাজে লাগিয়ে যে Programming করা হয় তাকেই বলা হয় Object Oriented Programming। যে প্রকার প্রোগ্রামিং এ অনেক অনেক অবজেক্ট কে নিয়ে বা অবজেক্ট কে ঘিরে প্রোগ্রামিং করা হয় তাকে OOP বা অবজেক্ট ওরিয়েন্টেড প্রোগ্রামিং বলে।

### Object: 
আমরা আমাদের চার পাশে যা কিছু দেখি তার সবই Object বা বস্তু। এই ধরুন আপনি আপনার নিজেকে এবং আপনার আসে-পাশের দিকে খেয়াল করুন , আপনার গায়ের জামা, আপনার পরনের প্যান্ট, হাতের মোবাইল, পড়ার টেবিল,বসার চেয়ার ,কম্পিউটার এই সবই একেকটি Object বা বস্তু। এমনকি আপনি / আমি নিজেও একটা Object.

``` php
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
class Car {
  // The code
}
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
### Inheritance:
Inheritance মানে হল বংশ পরিক্রমা। আপনি আপনার বাবার থেকে এসেছেন। আপনার বাবা আপনার দাদার থেকে এসেছেন। এটাই হল inheritance. যেমনঃ Form1:Form নির্দেশ করে Form নামের ক্লাস থেকে Form1 নামের একটি object হয়ে এসেছে। এখানে “:” inheritance নির্দেশ করে।

``` 
<?php
class Fruit {
  public $name;
  public $color;
  public function __construct($name, $color) {
    $this->name = $name;
    $this->color = $color;
  }
  public function intro() {
    echo "The fruit is {$this->name} and the color is {$this->color}.";
  }
}

// Strawberry is inherited from Fruit
class Strawberry extends Fruit {
  public function message() {
    echo "Am I a fruit or a berry? ";
  }
}
$strawberry = new Strawberry("Strawberry", "red");
$strawberry->message();
$strawberry->intro();
?>
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
?> 
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



How to use code? 'Hello Github'

#### To use Python Code
``` python
(train_images, train_labels), (test_images, test_labels) = tf.keras.datasets.mnist.load_data()

train_labels = train_labels[:1000]
test_labels = test_labels[:1000]

train_images = train_images[:1000].reshape(-1, 28 * 28) / 255.0
test_images = test_images[:1000].reshape(-1, 28 * 28) / 255.0
```

##### To use HTML
``` html
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
##### To use C#
```
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

##### To use Java
```  Java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

~What is _markdown_ *and how does one use*~

> "Websites have great guildelines" ()

# Header 1
<ul>
<li> Test 1 </li>
<li> Test 2 </li>
<li> Test 3 </li>
</ul>

## Header 2
<ol>
<li> Test 1 </li>
<li> Test 2 </li>
<li> Test 3 </li>
</ol>

### Header 3
 - This is a list test using Minus sign
 - This test proves true
 - Test is successful
 - Complete

#### header 4
 + This is a list test using + sign
 + This test proves true
 + Test is successful
 + Complete

##### header 5
1. Num keys in random orders list in order
232. This test proves true
3432. Test is successful
45632. Complete

###### header 6
1. Random orders with Indentation combines lines
      232. This test proves true
    3432. Test is successful
  45632. Complete

# <P> "This is an example" </p>



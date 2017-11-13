# UnitVsIntegration

What is Unit Testing ? Simply .. it a function that tests a unit of work . 

Why Do we write a unit Test ? .. 

1-So you dont get fired . 
2-Mistakes are part of being programmer .. they always happen and always should be fixed . 
3-In time of mistakes .. you dont have to go thrugh the whole code .. you need to know where the error is ? 


Technical Example Of Unit Test .. 

int combineNumbers(int a , int b ) {

return a + b ; 

}

void TestCombineNumbers() {
    Assert.IsEqual(CombineNumbers(5, 10), 15); // Assert is an object that is part of your test framework
    Assert.IsEqual(CombineNumbers(1000, -100), 900);
}

When you run the tests, you will be informed that these tests have passed. Now that you've built and run the tests,
you know that this particular function, or unit, will perform as you expect.

--------

what is integration testing . 

refers to joining all the components resulting in the complete system.

for example you have to test the keyboard of a computer than it is a unit testing but when you have to combine
the keyboard and mouse of a computer together to see its working or not than it is the integration testing.


![alt text](https://preview.ibb.co/hNG9Hb/Screenshot_from_2017_11_13_13_56_52.png)
![alt text](https://image.ibb.co/dV1yAw/Screenshot_from_2017_11_13_13_57_38.png)
![alt text](https://preview.ibb.co/khwn3G/Screenshot_from_2017_11_13_13_58_18.png)
![alt text](https://preview.ibb.co/kqQ3cb/Screenshot_from_2017_11_13_14_04_04.png)
![alt text](https://preview.ibb.co/b6VrVw/Screenshot_from_2017_11_13_14_04_27.png)
![alt text](https//preview.ibb.co/m9CuiG/Screenshot_from_2017_11_13_14_05_51.png)

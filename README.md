> # SimpleCalculator

## This program performs the simplest _arithmetic and algebraic_ operations.

---

![img1](images/image.png)

---

### Now familiarize yourself with the methods of the program.

1. tyr-catch method:

```cs
...
try
{
    Console.Write("Enter first number: ");
    int firstNumber = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine("Converting.....");


    Console.Write("Enter second number: ");
    int secondNumber = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine("Converting.....");
    Console.WriteLine("");
    Console.WriteLine("Calculation process completed.....");
    Console.WriteLine("");

    AddingMethod(firstNumber, secondNumber);
    SubtractingMethod(firstNumber, secondNumber);
    MultipleyingMethod(firstNumber, secondNumber);
    DividingMethod(firstNumber, secondNumber);
    SquareRootMethod(firstNumber, secondNumber);
    PowMethod(firstNumber, secondNumber);
}
catch (Exception e)
{
    Console.WriteLine("the value you entered cannot be converted to a number !");
    Console.WriteLine("Please enter a number !");
}
...

```
2. Arifmetic methods:

```cs
...
static void AddingMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"When added : {firstNumber + secondNumber}");
}

static void SubtractingMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"When subtracted : {firstNumber - secondNumber}");
}

static void MultipleyingMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"When multiplied : {firstNumber * secondNumber}");
}

static void DividingMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"When divided : {firstNumber / secondNumber}");
}
...

```
3. Algebraic methods:

```cs
...
static void SquareRootMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"When rooting: The square root of {firstNumber} is {Math.Sqrt(firstNumber)}");
    Console.WriteLine($"When rooting: The square root of {secondNumber} is {Math.Sqrt(secondNumber)}");
}

static void PowMethod(int firstNumber, int secondNumber)
{
    Console.WriteLine($"The square and cube of the '{firstNumber}': {Math.Pow(firstNumber, 2)} , {Math.Pow(firstNumber, 3)}");
    Console.WriteLine($"The square and cube of the '{secondNumber}': {Math.Pow(secondNumber, 2)} , {Math.Pow(secondNumber, 3)}");
}
...

```

4. Result:

![result](images/image1.png)
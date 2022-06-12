**Database Challenges**

**QUESTION 1**

I will take out cellphone details from the Employee table and make a new table. This new will be Cellphone which will have a cellphone number (cellphoneNum) as a primary key. The Event Detail table will be dependent on the cellphone table. In addition, the entities and variables should not have spaces in between. 

**QUESTION 2**

select m.genre, count(*)
from Tickets t 
join Movies m on t.MoviesId-m.MoviesID
group B


**Back-end Code Challenges**

**QUESTION 1**

public class Testing
{
    public static void Main()
    {
        string str; 
        int l = 0;

        Console.Write("\n\nFind the length of a string :\n");
        Console.Write("---------------------------------\n");
        Console.Write("Input the string : ");
        str = Console.ReadLine();

        foreach (char chr in str)
        {
            l += 1;

        }

        if (l<3)
        {
            Console.Write("Stack");
        }

        if (l>2 && l<5)
        {
            Console.Write("Overflow");
        }

        else if (l>4)
        {
            Console.Write("Stack Overflow!");
        }
    }
}

**Question 2**

public class Animal
{
    public String Eat()
    {
        return "Yummy";
    }

    public String MakeNoise()
{
    return "Durrr";
}

}

class Horse extends Animal
{

    @Override
    public String MakeNoise()
    {
        return "Neigh";
    }
}

class Sheep extends Animal
{
    @Override
    public String MakeNoise(){
    return  "Baaah";
    }
}


**Front-end Code Challenges**

**Question 1**

1. FirstDiv is Red and secondDiv is Orange

2. <!DOCTYPE html>
<div id="firstDiv" class="pink-card"/>
<div id="secondDiv" class="red-card"/>

        <style>
    #secondDiv {
        background: orange;
    }

    div {
        height: 150px;
        width: 150px;
        background: green;
    }

    .red-card {
        background: red;
    }

    .yellow-card {
        background: yellow;
    }

     .pink-card {
        background: pink;
    }
</style>

3.
<div id="firstDiv" class="pink-card"/>
<div id="secondDiv" class="yellow-card"/>

        <style>
    #Orange-card {
        background: orange;
    }

    div {
        height: 150px;
        width: 150px;
        background: green;
    }

    .red-card {
        background: red;
    }

    .yellow-card {
        background: yellow;
    }

     .pink-card {
        background: pink;
    }
</style>


Question 2
1.	Yes, will be parsed correctly
2.	I will use strict mode ("use strict";).




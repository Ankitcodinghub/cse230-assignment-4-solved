# cse230-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CSE230 Assignment 4 Solved](https://www.ankitcodinghub.com/product/cse230-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96166&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE230 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Minimal Submitted Files

You are required to turn in the following source file: assignment4.s

Objectives:

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
-write assembly language programs to:

-perform decision making using branch instructions.

-use syscall operations to display integers and strings on the console window

-use syscall operations to read integers from the keyboard.

Assignment Description:

Write a MIPS assembly language program that reads a customer’s current and previous meter readings of electricity and a month to compute its electricity bill.

If a customer spent 0 or less (technically this should not happen, though) KWH (kilowatt-hours) that is computed by current meter reading – previous meter reading,

then the program should print out “No bill to pay this month.\n”.

If a customer spent less than or equals to 250 KWH in a month, then the payment should be 25 dollars.

If a customer spent more than 250 KWH in a month of June, July, August, or September, then the bill amount is computed by:

bill amount= (KWH for the Month-250)/18 + 25;

If a customer spent more than 250 KWH in any other month, then the payment is compute by:

bill amount= (KWH for the Month-250)/20 + 25;

Then if the payment is greater than 0, it should print out the payment amount, along with its used KWH.

Name your source code file Assignment4.s.

The following shows how it looks like in a C program:

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>int newMeter;
int oldMeter;
int KWHforMonth;
int month;
</pre>
<pre>int billAmount;
printf("Please enter the new electricity meter reading:\n");
</pre>
<pre>//read an integer from a user input and store it in newMeter
scanf("%d", &amp;newMeter);
</pre>
<pre>printf("Please enter the old electricity meter reading:\n");
</pre>
<pre>//read an integer from a user input and store it in oldMeter
scanf("%d", &amp;oldMeter);
</pre>
<pre>printf("Please enter a month to compute their electricity bill,\n");
printf("Use an integer between 1 and 12 (1 for January, etc.):\n");
</pre>
<pre>//read an integer from a user input and store it in month
scanf("%d", &amp;month);
</pre>
<pre>KWHforMonth = newMeter - oldMeter;
</pre>
<pre>if (KWHforMonth &lt;= 0)
 {
</pre>
<pre>   printf("No bill to pay this month.\n");
 }
</pre>
else {

<pre>    //compute its bill
    if (KWHforMonth &lt;= 250)
</pre>
<pre>     {
       billAmount = 25;
</pre>
<pre>     }
    else if (KWHforMonth &gt; 250 &amp;&amp; month &gt;= 6 &amp;&amp; month &lt;= 9)
</pre>
<pre>     {
       billAmount = (KWHforMonth-250)/18 + 25;
</pre>
} else

<pre>     {
       billAmount = (KWHforMonth-250)/20 + 25;
</pre>
}

<pre>    //print out the billAmount
</pre>
<pre>    printf("Your total bill amount for this month: %d dollar(s) for %d KWH\n",
billAmount,    KWHforMonth);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>} //end of else
</pre>
</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/56799/pages/assignment4-due-wednesday-september-9th-5pm?module_item_id=3410171 3/6

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
9/8/2020 Assignment4 – Due: Wednesday, September 9th, 5pm: CSE 230: Computer Org/Assemb Lang Prog (2020 Fall)

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Here is a sample output (user input is in bold):

</div>
</div>
<div class="layoutArea">
<div class="column">
Please enter the new electricity meter reading:

15430

Please enter the old electricity meter reading:

15105

Please enter a month to compute their electricity bill,

Use an integer between 1 and 12 (1 for January, etc.):

5

Your total bill amount for this month: 28 dollar(s) for 325 KWH

———————————————–

Here is another sample output (user input is in bold):

Please enter the new electricity meter reading:

23705

Please enter the old electricity meter reading:

22190

Please enter a month to compute their electricity bill,

Use an integer between 1 and 12 (1 for January, etc.):

8

Your total bill amount for this month: 95 dollar(s) for 1515 KWH

———————————————–

Here is another sample output (user input is in bold): ———————————————–

Please enter the new electricity meter reading:

34525

Please enter the old electricity meter reading:

34291

Please enter a month to compute their electricity bill,

Use an integer between 1 and 12 (1 for January, etc.):

6

Your total bill amount for this month: 25 dollar(s) for 234 KWH

———————————————–

Here is another sample output (user input is in bold):

</div>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
———————————————–

</div>
</div>
<div class="layoutArea">
<div class="column">
Please enter the new electricity meter reading:

53205

Please enter the old electricity meter reading:

53205

Please enter a month to compute their electricity bill, Use an integer between 1 and 12 (1 for January, etc.): 4

No bill to pay this month.

</div>
</div>
</div>
</div>
</div>

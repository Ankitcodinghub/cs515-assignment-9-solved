# cs515-assignment-9-solved
**TO GET THIS SOLUTION VISIT:** [CS515 Assignment 9 Solved](https://www.ankitcodinghub.com/product/cs515-assignment-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100707&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS515 Assignment 9 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you need to develop a framework for comparing a set of the approximation algorithms whose objec- tives are same. After implementing those algorithms, you need to develop a comparative framework using shell script. Comparison of various algorithms will be done based on

• final output

• execution time

2 The algorithms that need to be considered

We are given a household H, which contains a set of appliances A that run for a total of T hours, {1…T}. The appliances can start working from the first till the T th time slot. There are 4 modes of operation for each appliance a ∈ A:

<ul>
<li>Slow: At every time slot for slow mode of operation, energy consumed in this mode=2 KWh and price paid by the household=1Rs.</li>
<li>Moderate: At every time slot for moderate mode of operation, energy consumed in this mode=4 KWh and price paid by the household=2Rs.</li>
<li>Fast: At every time slot for fast mode of operation, energy consumed in this mode=6 KWh and price paid by the household=4Rs.</li>
<li>OFF: At every time slot when the appliance is OFF, energy consumed in this mode=0 KWh and price paid by the household=0.75Rs.
Due to grid load constraints, at any time, a maximum of 2 appliances are allowed to operate in a single mode of operation. For example, if there are 7 appliances, maximum 2 can operate in slow mode, 2 in moderate, 2 in fast mode, and minimum one of them will have to be OFF. However, there is a minimum requirement of the household Rmin KWh per day, where the total energy consumed is the sum of the energy consumed by each appliance per time slot.

The total money paid by the household is based on the usage of these appliances in the entire day. Our objective is to schedule these appliances in a certain manner that the total money paid is minimum and Rmin is respected.

A list of algorithms is provided. For each of the following, consider two broad disciplines of scheduling: Queue Based (QB) and Random Based (RB). The approaches for any scheduling can be considered as follows.
</li>
</ul>
<ol>
<li>Fast charging first (FCF): Here, a Fast mode is assigned to two appliances, Moderate mode to the next two and so on, per time slot. The priority given is, Fast &gt; Moderate &gt; Slow.</li>
<li>Moderate charging first (MCF): Here, a Moderate mode is assigned to two appliances, Slow mode to the next two and so on, per time slot. The priority given is, Moderate &gt; Slow &gt; Fast.</li>
<li>Slow charging first (SCF): Here, a Slow mode is assigned to two appliances, Moderate mode to the next two and so on, per time slot. The priority given is, Slow &gt; Moderate &gt; Fast.</li>
</ol>
Note: Any appliance can be switched OFF as and when necessary. In all the approaches, the priorities work, iff the appliance is ON.

We have now 6 algorithms: QB FCF, QB MCF, QB SCF, RB FCF, RB MCS, RB SCF. In case of QB, the ordering of the above three approaches should be based on the placement of the appliances in a queue. As a convention, we can assume the appliances are in the order {a1, a2, a3, a4, a5} when |A|=5, with a1 being the front and a5 being the rear end. For RB, an appliance can be picked in any order. An example test case is provided, for your reference.

3 Sample Example

In the Fig. 1, the energy consumed in both the examples is 66KWh. However, the price paid in QB FCF is 45.75Rs, whereas in RB FCF is 43Rs.

Please note that the above examples are only for the explanation purpose and need not necessarily be optimal.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(a) QB FCF (b) RB FCF

Figure 1: An example figure for FCF using (a) the QB schedule, and (b) using RB schedule, when Rmin = 60. 4 Developing the Comparative Framework

These algorithms need to be run on various input sizes. On the same input data, all the algorithms must be run a fixed number of times. For all these different runs on the same input data, the output Price paid and execution time need to be recorded. The average of these will have to be used for comparison purpose. For better visualization, the average number of comparisons and execution times will have to be plotted using gnuplot tool.

One will use the following command in a linux shell to analyze the performance of various algorithms

<pre>$ ./testhouse -n &lt;A_size&gt; -t &lt;T&gt; -r &lt;R_min&gt; -s &lt;step_size&gt; -a &lt;avg&gt; -m [QB_FCF, QB_MCF, QB_SCF,
RB_FCF, RB_MCS, RB_SCF] -o &lt;out_filename&gt; -g &lt;plot_script_file_name&gt;
</pre>
<ul>
<li>n ⟨A size⟩ : To specify minimum number of appliances. Minimum value is 5.</li>
<li>t ⟨T⟩ : To specify the total time horizon in a day. Minimum value is 5.</li>
<li>r ⟨R min⟩ : To specify the minimum value of Rmin. Minimum value should be 50, and maximum value should be 300.</li>
<li>s ⟨step size⟩ : To specify the step size of the value of Rmin. Default value is 10.</li>
<li>a ⟨avg⟩ : An algorithm will be run avg number of times on the same input set and finally average will be taken as
an estimate for the performance measure. Default value of avg is 1.
</li>
<li>o ⟨out filename⟩ : Performance measure will be stored in this file. Default filename is output.txt.</li>
<li>g ⟨plot script file name⟩ : You need to generate gnuplot script to plot the output that you have obtained in output.txt. Default value is plot.gnu.</li>
<li>m [] : User can choose any number of methods out of the six methods – QB FCF, QB MCF, QB SCF, RB FCF, RB MCS, RB SCF. Default values are QB FCF and RB FCF.
Please note the followings-

<ol>
<li>You need to use the same input for all the algorithms specified by m option.</li>
<li>For your comparison graph for the execution time, the independent variable should be the values of Rmin and the dependent variable should be the average time taken.</li>
<li>For your comparison graph for the Price paid, the independent variable should be the values of Rmin and the dependent variable should be the corresponding average values obtained for Price paid.</li>
<li>For a given value of Rmin, any schedule that results in the total energy consumption between Rmin and Rmin+step size is a valid schedule.</li>
<li>Please provide makefile to build executable(s) for your C/C++ code</li>
</ol>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
5 Submission

Prepare a README.txt file containing the steps need to be followed.

All the necessary source files along with the README.txt should be archived to assign09.tgz. You can use tar -cvzf

assign09.tgz folderName to create such tgz file. Reference

1. GNUPLOT

<pre>     http://www.gnuplot.info/docs_4.0/gpcard.pdf
</pre>
2. Makefile

<pre>     http://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>

# cpeg422-project-4-convolutional-operation-acceleration-solved
**TO GET THIS SOLUTION VISIT:** [CPEG422 Project 4-Convolutional Operation Acceleration Solved](https://www.ankitcodinghub.com/product/cpeg422-project-4-convolutional-operation-acceleration-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95202&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPEG422 Project 4-Convolutional Operation Acceleration Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
&nbsp;

During this project, you will implement a convolution operation that is commonly used in convolutional neural networks (CNN) in both software and hardware. You are also required to make comparison between software and hardware implementations.

Goals of this project:

Learn how to write scalable VHDL code

Learn to do software and hardware co-design Learn to build embedded systems

Your tasks:

Task1: Implement the convolution operation for k 3×3 filters and an n x n matrix purely in software (c

code).

Task2: Implement a 3×3 convolution operation (one 3×3 filter and one 3×3 matrix) in hardware (FPGA).

Task3: Increase the matrix size in task2 to n x n, find the maximum number of convolution operations (9 x (n-2) x (n-2)) that can be done in parallel on the FPGA.

Task4: Compare the running time of software and hardware implementations for the same matrices. Suppose N × N is the maximum size of matrix you find. You need to compare N-2 different cases (for i = 3 to N). Find the exact point that the hardware starts to outperform software.

Task5: Increase the number of filters to K. Each time you update a filter value, the hardware will update the result matrix. Compare the running time of software and hardware implementations for different K values. Report the amount of speed up achieved by this approach.

Task6: Finally, submit your project report.

Minimal Hardware and Toolkit:

</div>
</div>
<div class="layoutArea">
<div class="column">
Vivado

Zybo

Xillinx SDK

Serial terminal (For observing communication between Processor and FPGA)

</div>
</div>
<div class="layoutArea">
<div class="column">
(For hardware IP and block design)

(For implementing block design and implementing communication system) (For software control on Processor side)

</div>
</div>
<div class="layoutArea">
<div class="column">
Convolutional Operation:

Assume A is a 3×3 filter and B is an n × n matrix. The output of a convolution operation is C=A*B, which C is an (n-2) × (n-2) matrix, is defined as:

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑐!!

C=!” ⋮

𝑐 (#$%)!

</div>
<div class="column">
⋯ 𝑐!(#$%)

⋱ ⋮ ‘( , 𝑐 = ∑’+% ∑(+% 𝑎 𝑏 ⋯ 𝑐 ‘( ),’ *,( )* )*

(#$%)(#$%)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
In this project, each element of A and B is 16-bit long, while each element of C is 32-bit long. The Multiply- Accumulate (MAC) unit can be used as the basic function unit to implement matrix multiplication. FPGA usually utilizes DSP units to perform MAC operations. Specifically, the Zynq FPGA contains 80 slices of DSPs, and each slice contains 2 basic MAC units.

Implementation details:

• Software implementation:

<ol>
<li>In task 1, Randomly generate integer values to construct your filters and the matrix.</li>
<li>Print out the result C matrix. You will have k result matrices for k filters. Make sure your results
are correct.
</li>
</ol>
• Hardware implementation:

<ol>
<li>The VHDL implementation can be RTL style (use operator ‘*’ and ‘+’).</li>
<li>The processor sends k 3×3 filters and one nxn matrix to the FPGA. For each filter, the FPGA
computes C and sends it to the processor.
</li>
<li>To implement and test your design, use the steps you learned in the previous project:
1) Finish your matrix multiplication VHDL code and package the IP.

2) Build a block design and generate bit stream.

3) Use SDK to program the FPGA. Write a C code to send inputs and get output from FPGA. 4) Observe the results on terminal and check its correctness.
</li>
</ol>
• Software vs. Hardware:

<ol>
<li>You can use system call in c to collect the running time. When you collect hardware running
time, make sure to include all set up time, data send and receive time.
</li>
<li>Compare your software output and hardware output for error checking.</li>
</ol>
Questions: (submit your answer together with the report)

<ol>
<li>Please describe your ideas to make your VHDL code scalable for different matrix size and different filters. Here “scalable” means your convolutional operation design can be easily changed for different combinations of (k, n). (Hint: define some parameters)</li>
<li>Regarding the maximum number of convolutional operations (9 x (n-2) x (n-2)) that can be done in parallel on FPGA, please analyze all the possible hardware resource constraints. For each possible bottleneck you find, what is the limited matrix size that can be held on FPGA? In your design, what is the most constrained bottleneck, and the maximum matrix size can be held in your design? (Hint: bottleneck types are related with resource category such as LUTs, DSPs, on-board block RAM size, I/O registers. Such information can be found in the manual. For each resource, show the constraint you find and compute the maximum matrix size based on it.)</li>
</ol>
Report requirements:

<ol>
<li>Design summary:

1) Summarize how you implement your software multiplication. 2) Summarize how you implement your hardware IP.</li>
<li>Result display:
<ol>
<li>1) &nbsp;Briefly describe how your C program controls the FPGA and communicates with it for
hardware implementation.
</li>
<li>2) &nbsp;Snapshot or paste your c code in different tasks.</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>3) &nbsp;Discuss possible hardware implementation bottlenecks. Describe the bottleneck in your implementation. Based on the found bottleneck of your implementation, compute the maximum matrix size. Show your steps of computation and explain the reason.</li>
<li>4) &nbsp;Make a comparison table and chart as well. Compare the running times of hardware implementation and software implementation, from size 1 to maximum.</li>
</ol>
<ol start="3">
<li>Design implementation report: You only need to report the maximum matrix hardware case. Summarize the block design implementation report offered in Vivado. Please report:
1) Hardware utilization of post-implementation (FF,IO ,LUT, BUF…) in table format. 2) Power report (dynamic vs. static, also signal, logic and I/O).

3) Timing report (critical path delay).

4) Design schematic snapshot.
</li>
<li>Summarize hardware and software implementation. Based on your design experience, give pro and cons for hardware and software implementations and some guidance for system designers.</li>
</ol>
</div>
</div>
</div>

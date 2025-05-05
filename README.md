# ve370-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [VE370 Homework 2 Solved](https://www.ankitcodinghub.com/product/ve370-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99096&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;VE370 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<ol>
<li>Following memory location has address 0x0F000000 and content 0x15C78933.
0123 0x0F000000 33 89 C7 15

Write RISC-V assembly instructions to load the byte C7 as a signed number into register x20, then show the content of x20 after the operations.
</li>
<li>&nbsp;The RISC-V assembly program below computes the factorial of a given input n (n!). The integer input is passed through register x12, and the result is returned in register x10. In the assembly code below, there are a few errors. Correct the errors.

FACT: addi sp, sp, 8

<pre>        sw x1, 4(sp)
        sw x12, 0(sp)
        add x18, x0, x12
        addi x5, x0, 2
        bge x12, x5, L1
        mul x10, x18, x10
        addi sp, sp, -8
        jalr x0, 0(x1)
</pre>
</li>
</ol>
<pre>  L1:   addi x12, x12, -1
        jal x1, FACT
</pre>
<pre>        addi x10, x0, 1
        lw x12, 4(sp)
        lw x1, 0(sp)
        addi sp, sp, -8
        jalr x0, 0(x1)
</pre>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>(10 points) Consider a proposed new instruction named rpt. This instruction combines a loop’s condition check and counter decrement into a single instruction. For example,
rpt x29, loop

would do the following:

<pre>     if (x29 &gt; 0) {
        x29=x29−1;
        goto loop;
</pre>
}

<ol>
<li>1) &nbsp;(5 points) If this instruction were to be added to the RISC-V instruction set, what is the most appropriate instruction format?</li>
<li>2) &nbsp;(5 points) What is the shortest sequence of RISC-V instructions that performs the same operation?</li>
</ol>
</li>
<li>(20 points) Implement the following C code in RISC-V assembly. Hint: Remember that the stack pointer must remain aligned on a multiple of 16.
<pre>      int fib(int n){
         if (n==0) return 0;
         else if (n==1) return 1;
         else return fib(n−1) + fib(n−2);
</pre>
}
</li>
<li>(10 points) For each function call in above problem, show the contents of the stack after the function call is made. Assume the stack pointer is originally at address 0x7ffffffc, and follow the register conventions.</li>
<li>(7 points) Given a 32-bit RISC-V machine instruction:
<pre>       1111 1111 0110 1010 0001 1010 1110 0011
</pre>
1) (6 points) What does the assembly instruction do? 2) (1 point) What type of instruction is it?
</li>
<li>(6 points) Given RISC-V assembly instruction:
<pre>       lw x21, -32(sp)
</pre>
1) (5 points) What is the corresponding binary representation?
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2) (1 point) What type of instruction is it?

<ol start="8">
<li>(12 points) If the RISC-V processor is modified to have 128 registers rather than 32 registers:
1) (4 points) show the bit fields of an R-type format instruction assuming opcode and func fields are not changed.

2) (4 points) What would happen to the I-type instruction if we want to keep the total number of bits for an instruction unchanged?

3) (4 points) What is the impact on the range of addresses for a beq instruction? Assume all instructions remain 32 bits long and the size of opcode and func fields don’t change.
</li>
<li>(20 points) Convert the following assembly code fragment into machine code, assuming the memory location of the first instruction (LOOP) is 0x1000F400
<pre>       LOOP:     blt x0, x5, ELSE
                 jal x0, DONE
</pre>
<pre>       ELSE:     addi x5, x5, -1
                 addi x25, x25, 2
</pre>
<pre>                 jal x0, LOOP
       DONE:     ...
</pre>
</li>
</ol>
</div>
</div>
</div>

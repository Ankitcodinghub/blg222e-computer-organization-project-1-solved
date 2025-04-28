# blg222e-computer-organization-project-1-solved
**TO GET THIS SOLUTION VISIT:** [BLG222E Computer Organization Project 1 Solved](https://www.ankitcodinghub.com/product/blg222e-computer-organization-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;72033&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;BLG222E Computer Organization  Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

&nbsp;

&nbsp;

In this project, registers and register files will be designed and implemented. It has 4 parts. Design each part <strong>as a library unit</strong>, so that it can be reused in other parts. <strong>You can use any available combinational/sequential logisim units in your projects. </strong>

&nbsp;

<strong>(Part-1)</strong> Design 2 different types of registers: <strong>(1)</strong> 8-bit register and <strong>(2)</strong> 16-bit register.

&nbsp;

<strong>(Part-1a)</strong> The 8-bit register has 4 functionalities that are controlled by 2-bit control signals (<strong>FunSel</strong>) and an enable input (<strong>E</strong>).

The block diagram of the 8-bit register and the function table is shown in Figure 1. Symbol 𝜙 means don’t care. Build the register as a library in logisim software so that you can use them in other parts.

<table width="274">
<tbody>
<tr>
<td width="34"></td>
<td width="58"></td>
<td width="71"></td>
<td width="111"></td>
</tr>
<tr>
<td width="34">0</td>
<td width="58">ɸ</td>
<td width="71">Q</td>
<td width="111">(Retain Value)</td>
</tr>
<tr>
<td width="34">1

1

1 1
</td>
<td width="58">00

01

10 11
</td>
<td width="71">Q-1

Q+1

I

0
</td>
<td width="111">(Decrement)

(Increment)

(Load)

(Clear)
</td>
</tr>
</tbody>
</table>
<sup>I&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>E&nbsp;&nbsp;&nbsp;&nbsp; FunSel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Q<sup>+</sup>

E&nbsp;&nbsp;&nbsp; FunSel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Q

<h1>Figure 1: Block Diagram of the registers (Left) and the function table (Right)</h1>
&nbsp;

<strong>(Part-1b)</strong> Design an 16-bit<strong> IR</strong> register whose block diagram and function table are given in Figure 2.

This register can store 16 bit binary data. However, the input of this register file is only 8 bits. Hence, using the 8 bit input you can load either the lower (bits 7-0) or higher (bits 15-8) half. This is determined by 𝑳/𝑯 &nbsp;signal.

<h1>Figure 2: Graphic symbol of the IR register (Left) and its characteristic table (Right)</h1>
<strong>&nbsp; </strong>

<strong>(Part-2)</strong> Design a register file (a structure that contains many registers) that works as follows.

&nbsp;

<strong>(Part-2a) </strong>Design the system shown in Figure 3 which consists of four 8-bit general purpose registers:<strong> R1</strong>, <strong>R2</strong>,<strong> R3,</strong> and <strong>R4 </strong>and four 8-bit temporary registers:<strong> T1</strong>, <strong>T2</strong>,<strong> T3,</strong> and <strong>T4</strong>. The details of inputs and outputs are as follows.

<h1>Figure 3: 8-bit general purpose and temporary registers, inputs, and outputs</h1>
<strong>OutASel</strong> and <strong>OutBSel</strong> are used to feed output lines <strong>OutA</strong> and <strong>OutB</strong>, respectively. 8 bits of the selected registers are output to <strong>OutA</strong> and <strong>OutB</strong>. Figure 4 shows selection of output registers based on the <strong>OutASel</strong> and <strong>OutBSel</strong> control inputs.

OutASel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; OutA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; OutBSel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; OutB

<table width="142">
<tbody>
<tr>
<td width="142">R1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 000 R2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 001

R3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 010

R4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 011
</td>
</tr>
<tr>
<td width="142">T1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 100

T2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 101

T3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 110 T4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 111
</td>
</tr>
</tbody>
</table>
000R1

001R2

010R3

011R4

100T1

101T2

110T3

111T4

&nbsp;

<h1>Figure 4: OutASel and OutBSel controls</h1>
<strong>RegSel</strong> and <strong>TmpSel</strong> are 4-bit signals that select the registers to apply the function that is determined by the 2-bit <strong>FunSel </strong>(<em>Figure 5</em>) signal. The selectes register by <strong>Regsel</strong> and <strong>TmpSel</strong> are shown in <em>Figure 6</em> and <em>Figure 7</em>, respectively.

+

<table width="222">
<tbody>
<tr>
<td width="70">FunSel</td>
<td width="55">R<sub>x</sub></td>
<td width="96"></td>
</tr>
<tr>
<td width="70">00 01

10 11
</td>
<td width="55">R<sub>x</sub>-1

R<sub>x</sub>+1

I

0
</td>
<td width="96">(Decrement)

(Increment)

(Load)

(Clear)
</td>
</tr>
</tbody>
</table>
<h1>Figure 5: FunSel Control Input</h1>
RegSel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Enabled General Purpose Registers

0000&nbsp;&nbsp;&nbsp;&nbsp; ALL general purpose registers are enabled (Function selected by FunSel will be applied to R1, R2, R3 and R4)

0001&nbsp;&nbsp;&nbsp;&nbsp; R1, R2 and R3 are enabled (Function selected by FunSel will be applied to R1, R2 and R3)

0010&nbsp;&nbsp;&nbsp;&nbsp; R1, R2 and R4 are enabled, Function selected by FunSel will be applied to R1, R2 and R4

0011&nbsp;&nbsp;&nbsp;&nbsp; R1 and R2 are enabled (Function selected by FunSel will be applied to R1 and R2)

0100&nbsp;&nbsp;&nbsp;&nbsp; R1, R3 and R4 are enabled (Function selected by FunSel will be applied to R1, R3 and R4)

0101&nbsp;&nbsp;&nbsp;&nbsp; R1 and R3 are enabled (Function selected by FunSel will be applied to R1 and R3)

0110&nbsp;&nbsp;&nbsp;&nbsp; R1 and R4 are enabled (Function selected by FunSel will be applied to R1 and R4)

0111&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Only R1 is enabled (Function selected by FunSel will be applied to R1)

<ul>
<li>R2, R3 and R4 are enabled (Function selected by FunSel will be applied to R2, R3 and R4)</li>
<li>R2 and R3 are enabled (Function selected by FunSel will be applied to R2 and R3)</li>
<li>R2 and R4 are enabled (Function selected by FunSel will be applied to R2 and R4)</li>
<li>Only R2 is enabled (Function selected by FunSel will be applied to R2)</li>
<li>R3 and R4 are enabled (Function selected by FunSel will be applied to R3 and R4)</li>
<li>Only R3 is enabled (Function selected by FunSel will be applied to R3)</li>
<li>Only R4 is enabled (Function selected by FunSel will be applied to R4)</li>
<li>N0 general purpose register is enabled (All R1, R2, R3 and R4 registers retain their values) <em>Figure 6: RegSel Control Input </em></li>
</ul>
<em>&nbsp;</em>

TmpSel&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Enabled Temporary Registers

0000&nbsp;&nbsp;&nbsp;&nbsp; ALL temporary registers are enabled (Function selected by FunSel will be applied to T1, T2, T3 and T4)

0001&nbsp;&nbsp;&nbsp;&nbsp; T1, T2 and T3 are enabled (Function selected by FunSel will be applied to T1, T2 and T3)

0010&nbsp;&nbsp;&nbsp;&nbsp; T1, T2 and T4 are enabled, Function selected by FunSel will be applied to T1, T2 and T4

0011&nbsp;&nbsp;&nbsp;&nbsp; T1 and T2 are enabled (Function selected by FunSel will be applied to T1 and T2)

0100&nbsp;&nbsp;&nbsp;&nbsp; T1, T3 and T4 are enabled (Function selected by FunSel will be applied to T1, T3 and T4)

0101&nbsp;&nbsp;&nbsp;&nbsp; T1 and T3 are enabled (Function selected by FunSel will be applied to T1 and T3)

0110&nbsp;&nbsp;&nbsp;&nbsp; T1 and T4 are enabled (Function selected by FunSel will be applied to T1 and T4)

0111&nbsp;&nbsp;&nbsp;&nbsp; Only T1 is enabled (Function selected by FunSel will be applied to T1)

<ul>
<li>T2, T3 and T4 are enabled (Function selected by FunSel will be applied to T2, T3 and T4)</li>
<li>T2 and T3 are enabled (Function selected by FunSel will be applied to T2 and T3)</li>
<li>T2 and T4 are enabled (Function selected by FunSel will be applied to T2 and T4)</li>
<li>Only T2 is enabled (Function selected by FunSel will be applied to T2)</li>
<li>T3 and T4 are enabled (Function selected by FunSel will be applied to T3 and T4)</li>
<li>Only T3 is enabled (Function selected by FunSel will be applied to T3)</li>
<li>Only T4 is enabled (Function selected by FunSel will be applied to T4)</li>
<li>N0 temporary register is enabled (All T1, T2, T3 and T4 registers retain their values)</li>
</ul>
<h1>Figure 7: TmpSel Control Input</h1>
<strong>&nbsp;</strong>

<strong>For example:</strong> If <strong>RegSel</strong> is 1001, <strong>TmpSel</strong> is 1111, and <strong>FunSel</strong> is 01, then the registers <strong>R2</strong> and <strong>R3</strong> will be incremented with next clock cycle. <strong>R1</strong> and <strong>R4</strong> will not be affected since they are not enabled by <strong>RegSel</strong>. Similarly, temporary registers <strong>T1</strong>, <strong>T2</strong>, <strong>T3</strong>, <strong>T4</strong> will not be affected since they are not enabled by <strong>TmpSel</strong>.

&nbsp;

&nbsp;

<strong>(Part-2b) </strong>Design the <strong>address register file (ARF)</strong> system shown in Figure 8 which consists of three 8-bit address registers: <strong>program counter (PC), address register (AR), and stack pointer (SP)</strong>.&nbsp; FunSel and Regsel works as in <strong>Part-2a</strong>.

<h1>Figure 8: 8-bit address registers, inputs, and outputs</h1>
<strong>OutCSel</strong> and <strong>OutDSel</strong> are used to feed output lines <strong>OutC</strong> and <strong>OutD</strong>, respectively. 8 bits of the selected registers are output to <strong>OutC</strong> and <strong>OutD</strong>. Figure 9 shows selection of output registers based on the <strong>OutCSel</strong> and <strong>OutDSel</strong> control inputs.

<h1>Figure 9: OutCSel and OutDSel controls</h1>
<strong>&nbsp;</strong>

<strong>(Part-3)</strong> Design an Arithmetic Logic Unit (ALU) that has two 8-bit inputs, an 8-bit output, and a

4-bit output for <strong>z</strong>ero, <strong>n</strong>egative, <strong>c</strong>arry, and <strong>o</strong>verflow flags. The ALU is shown on the left side of&nbsp; Figure 10. The ALU functions and the flags that will be updated (i.e., <strong>–</strong> means that the flag will not be affected and <strong>√</strong> means that the flag changes based on the OutALU) are given on the right side of Figure 10:

<ul>
<li><strong>FunSel</strong> selects the function of the ALU.</li>
<li><strong>OutALU </strong>shows the result of the operation that is selected by <strong>FunSel</strong> and applied on A and/or B inputs.</li>
<li><strong>Arithmetic operations</strong> are done using <strong>2’s complement </strong></li>
<li><strong>Z (zero) </strong>bit is set if <strong>OutALU</strong> is zero (e.g., when <strong>NOT B </strong>is zero).</li>
<li><strong>C (carry) </strong>bit is set if <strong>OutALU</strong> sets the carry (e.g., when <strong>LSL A </strong>produces carry).</li>
<li><strong>N (negative) </strong>bit is set if the ALU operation generates a negative result (e.g., when <strong>A–B </strong>results in a negative number).</li>
<li><strong>O (overflow) </strong>bit is set if an overflow occurs (e.g., when <strong>A+B</strong> results in an overflow)<strong>.</strong></li>
<li>Note that <strong>Z|C|N|O</strong> flags are stored in a <strong>register! </strong></li>
</ul>
<table width="582">
<tbody>
<tr>
<td width="281"></td>
<td width="302">&nbsp;

<table width="290">
<tbody>
<tr>
<td width="54">FunSel</td>
<td width="96">OutALU</td>
<td width="47">Z</td>
<td width="31">C</td>
<td width="19">N</td>
<td width="41">O</td>
</tr>
<tr>
<td width="54">0000

0001
</td>
<td width="96">A

B
</td>
<td width="47">&nbsp;

&nbsp;
</td>
<td width="31">&nbsp;

&nbsp;
</td>
<td width="19">&nbsp;

&nbsp;
</td>
<td width="41">&nbsp;

&nbsp;
</td>
</tr>
<tr>
<td width="54">0010

0011
</td>
<td width="96">NOT A NOT B</td>
<td width="47">&nbsp;

&nbsp;
</td>
<td width="31">&nbsp;

&nbsp;
</td>
<td width="19">&nbsp;

&nbsp;
</td>
<td width="41">&nbsp;

&nbsp;
</td>
</tr>
<tr>
<td width="54">0100

0101

0110
</td>
<td width="96">A + B

A + B + Carry

A – B
</td>
<td width="47">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="31">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="19">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="41">&nbsp;

&nbsp;

&nbsp;
</td>
</tr>
<tr>
<td width="54">0111

1000

1001
</td>
<td width="96">A AND B

A OR B

A XOR B
</td>
<td width="47">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="31">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="19">&nbsp;

&nbsp;

&nbsp;
</td>
<td width="41">&nbsp;

&nbsp;

&nbsp;
</td>
</tr>
<tr>
<td width="54">1010

1011

1100

1101

1110

1111
</td>
<td width="96">LSL A

LSR A

ASL A

ASR A

CSL A

CSR A
</td>
<td width="47">&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
</td>
<td width="31">&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
</td>
<td width="19">&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
</td>
<td width="41">&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
&nbsp;

<h1>Figure 10: The ALU (Left) and its characteristic table (Right)</h1>
&nbsp;

<strong>(C</strong>ircular | <strong>A</strong>rithmetic | <strong>L</strong>ogical) <strong>S</strong>hift (<strong>L</strong>eft | <strong>R</strong>ight) operations are depicted in <em>Figure 11</em>, <em>Figure 12</em><em>, and </em><em>Figure 13</em>.

<h1>Figure 11: Circular Shift Operations</h1>
<em>&nbsp;</em>

<em>&nbsp;</em>

<em>Figure 12: Logical Shift Operations </em>

<em>&nbsp;</em>

<em>&nbsp;</em>

<em>Figure 13: Arithmetic Shift Operations </em>

<em>&nbsp;</em>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>(Part-4) </strong>Implement the organization in Figure 14. Please note that, <strong>the whole system uses&nbsp; the same single clock. </strong>

<h1>Figure 14: ALU System</h1>
<strong>&nbsp;</strong>

&nbsp;

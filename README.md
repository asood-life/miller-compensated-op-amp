<h3>Table of Contents</h3>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#implementation">Implementation</a></li>
    <li><a href="#installation-and-setup">Installation and Setup</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#results-and-performance">Results and Performance</a></li>
    <li><a href="#future-work">Future Work</a></li>
    <li><a href="#team">Team</a></li>
</ul>

<h3 id="introduction">Introduction</h3>
<div>
    <p>
        The project aims to design a <b>two-stage Miller-compensated operational amplifier</b> (op-amp) that is optimized for driving a<b> capacitive load</b>. The circuit diagram for this design is illustrated below.
    </p>
    <p><img width="600" src="./assets/circuit-diagram.png"></p>
</div>

<h3 id="overview">Overview</h3>
<div>
    <h4>Two-Stage Miller-Compensated Op-Amp with a Capacitive Load</h4>
    <p>
        A two-stage Miller-compensated op-amp consists of two main amplification stages with compensation applied to ensure stability, especially when driving capacitive loads. The Miller compensation technique involves using a compensation capacitor to create a dominant pole, thereby enhancing the phase margin and ensuring stable operation.
    </p>
</div>
<div>
    <p>
        <b>First Stage: Differential Amplifier</b>: The first stage of the op-amp is a differential amplifier, which provides the initial amplification and high input impedance. It typically consists of a pair of transistors configured to amplify the difference between the input signals.
    </p>
</div>
<div>
    <p>
        <b>Second Stage: Gain Stage</b>: The second stage is a gain stage that further amplifies the signal. This stage is usually a common-source amplifier, which provides high gain and drives the output stage.
    </p>
</div>
<div>
    <p>
        <b>Miller Compensation</b>: Miller compensation is implemented by connecting a compensation capacitor between the output of the first stage and the input of the second stage. This capacitor introduces a dominant pole, which reduces the gain at higher frequencies and improves the phase margin, thus enhancing the stability of the amplifier.
    </p>
</div>
<div>
    <p>
        <b>Capacitive Load</b>: In applications where the op-amp needs to drive a capacitive load, the Miller-compensated design is particularly beneficial. Capacitive loads can cause phase shift and potentially lead to instability. The compensation capacitor helps mitigate these effects by controlling the frequency response of the amplifier.
    </p>
</div>
<div>
    <h4>Circuit Analysis and Design Specifications</h4>
    <table>
        <tr>
            <th>Parameter</th>
            <th>Value</th>
        </tr>
        <tr>
            <td>A<sub>V<sub>0</sub></sub></td>
            <td>50 dB</td>
        </tr>
        <tr>
            <td>Gain-Bandwidth</td>
            <td>8 MHz</td>
        </tr>
        <tr>
            <td>PM</td>
            <td>45<sup>o</sup></td>
        </tr>
        <tr>
            <td>CMRR</td>
            <td>60 dB</td>
        </tr>
        <tr>
            <td>CL</td>
            <td>30 pF</td>
        </tr>
        <tr>
            <td>Power Dissipated</td>
            <td>500 μW</td>
        </tr>
        <tr>
            <td>Slew Rate</td>
            <td>10 V/μs</td>
        </tr>
    </table>
</div>

<h3 id="implementation">Implementation</h3>


<h3 id="installation-and-setup">Installation and Setup</h3>


<h3 id="usage">Usage</h3>


<h3 id="results-and-performance">Results and Performance</h3>


<h3 id="future-work">Future Work</h3>


<h3 id="team">Team</h3>
<div>
    <table>
        <tr align="center">
            <td>
                <img width="100" src="https://avatars.githubusercontent.com/u/148894491?v=4"><br>
                <a href="https://github.com/asood-life">Akshat Sood</a>
            </td>
        </tr>
    </table>
</div>
<hr>
<div>
    Thank you for visiting! If you find value in this project, please consider giving it a ⭐ star. Your support is greatly appreciated and assists others discover the project.
    <br>
    If you have any requests for enhancements or find any bugs, please report them under <a href="https://github.com/asood-life/miller-compensated-op-amp/issues">Issues</a>. Your feedback is invaluable in making this project better for everyone.
</div>

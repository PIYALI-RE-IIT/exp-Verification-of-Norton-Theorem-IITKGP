### Theory
<p> A linear active network consisting of independent and(or) dependent voltage and current sources and linear bilateral network elements can be replaced by an equivalent circuit consisting of current sources in parallel with the resistance, the current source being the short circuited current across the load terminal and resistance being the internal resistance of the source network looking through the open circuited load terminals. In order to find the current through<b>R<sub>L</sub></b>, the load resistance of the figure 1 by Norton's theorem, let,replace <b>R<sub>L</sub></b> by short circuit as shown in figure 2.</p>
<!-- <h2><span style="background-color: rgb(255, 255, 255);">Circuit diagram:</span></h2><br> -->
<br><figure style="text-align:center">
<img alt="" src="images/pic1.jpg" style="width:400px;height:350px;">
<figcaption>[Fig 1: Circuit with source V<sub>S</sub> and Load R<sub>L</sub>]</figcaption>
</figure>									
<figure style="text-align:center">
<img alt="" src="images/pic2.jpg" style="width:400px;height:350px;">
<figcaption>[Fig 2: Circuit with <b>R<sub>L</sub></b> shorted]
</figcaption>
</figure>
<p>Obviously, in Fig 2;
$$I=\frac{V_s}{R_1+\frac{R_2 * R_3}{R_2 + R_3}}$$ <br>
$$I_{s/c}= I\frac{R_3}{R_3 + R_2}$$<br>
Next, the short circuit is removed and the independent source is deactivated as shown in figure 3.</p>
<br><figure style="text-align:center">
<img alt="" src="images/pic3.jpg" style="width:400px;height:350px;">
<figcaption>
[Fig 3: Circuit with source V<sub>s</sub> deactivated and Load R<sub>L</sub> open]
</figcaption>
</figure><p>From Fig 3;
$$R_{int}= R_2+ \frac{R_1*R_3}{R_1+R_3}$$
<br>
As per Norton's theorem , the equivalent circuit as shown in figure 4, would contain a current source in parallel to the internal resistance, the current source being the short circuited current across the shorted terminals of the load resistor.</p>
<br><figure style="text-align:center">
<img alt="" src="images/pic4.jpg" style="width:400px;height:350px;">
<figcaption>[Fig 4: Norton equivalent circuit]
</figcaption>
</figure>									
<p>Obviously, from Fig 4;<br>
$$I_{L}= I_{s/c}\frac{R_{int}}{R_{int}+R_L}$$
</p><br><br><br>
</p>
</div>
                    
<p>For your unit 1 assignment, you must first install the Netbeans development and the Java Software Development Kit and test the installation. Detailed instructions for doing this are provided in the unit overview. Students who are using the virtual computing lab will not be required to install the software as this has already been completed. Students who will be using mobile computing devices should consider creating a free account at www.programr.com and creating a Java project in which to complete this (and future) assignments.</p>
<p>In this assignment, you will create a program that computes the distance an object will fall in Earth's gravity.</p>
<ol>
<li>Create a new class called GravityCalculator.</li>
<li>Copy and paste the following initial version:</li>
</ol>
<pre>  	import java.io.*;

public class GravityCalculator {

	public static void main(String[] arguments){

		double  gravity =-9.81; // Earth's gravity in m/s^2

		double  initialVelocity = 0.0; // starting velocity of the object

		double  fallingTime = 10.0; // time in seconds that the object falls

		double  initialPosition = 1000.0; // Starting position in meters, the calculation will 		determine the ending position in meters

		double  finalPosition = 0.0;

		System.out.println("The object's position after " + fallingTime +" seconds is 			"+finalPosition + " m.");

	}
}
  </pre>
<ol start="3">
<li>Run it</li>
<li>Modify the example program to compute the position of an object after falling for 10 seconds, outputting the position in meters. The formula in Math notation is:</li>
</ol>
<p class="text-center">x(t) = 0.5at^2 + vit + xi</p>
<table class="table table-condensed">
<thead>
<tr>
<th>
<p>Variable</p>
</th>
<th>
<p>Meaning</p>
</th>
<th>
<p>Value</p>
</th>
</tr>
</thead>
<tbody>
<tr>
<td>a</td>
<td>Acceleration (m/s2)</td>
<td>-9.81</td>
</tr>
<tr>
<td>t</td>
<td>Time (s)</td>
<td>10</td>
</tr>
<tr>
<td>vi</td>
<td>Initial velocity (m/s)</td>
<td>0</td>
</tr>
<tr>
<td>xi</td>
<td>Initial position</td>
<td>1000</td>
</tr>
</tbody>
</table>
<p>Submit your GravityCalculator.java file along with the output you received when running it. The output should be captured as a screen capture or by cutting and pasting the output from the window that the output of your program is displayed in.</p>

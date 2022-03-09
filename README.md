# Information content vs percentage
Information content vs percentage

The objective digital stain (ODS) is represented by a distribution of points on a two-dimensional (2D) image, which reflects the information structure inside a DNA/RNA sequence. But from where do we get the <kbd>x-axis</kbd> and <kbd>y-axis</kbd> of each point? In order to build an ODS, a scanner that uses sliding windows must be developed first. The <kbd>x-axis</kbd> values and the <kbd>y-axis</kbd> values for a point are calculated from the content of a sliding window. One value for the <kbd>x-axis</kbd> is computed using an algorithm called [self-sequence alignment](https://github.com/Gagniuc/Self-sequence-alignment), and the <kbd>y-axis</kbd> value for a point is computed using the relative frequency of <kbd>C </kbd>plus <kbd>G</kbd> letters from the sliding window. Since the content of each sliding window provides a point on the image, a visible shape starts to reveal itself. In turn, the shape of the distribution pushes the association of the method with a kind of “digital stain,” thus safely establishing the name of the method. In the past, ODSs were simply called “DNA patterns”. 

Note that the construction and theory behind the chart of this application can be found [here](https://github.com/Gagniuc/World-smallest-js-chart-v1.0).

# Live demo

https://gagniuc.github.io/Information-content-vs-percentage/

<kbd><img src="https://github.com/Gagniuc/Information-content-vs-percentage/blob/main/%5BG%5D%20Information%20content%20vs%20percentage.png" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>

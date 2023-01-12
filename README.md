# GitHub MathML test

- Axiom of power set
  <math display="block">
    <mrow>
      <mo rspace="0">&forall;</mo>
      <mi>A</mi>
      <mo lspace="mediummathspace" rspace="0">&exist;</mo>
      <mi>P</mi>
      <mo lspace="mediummathspace" rspace="0">&forall;</mo>
      <mi>B</mi>
      <mspace width="thinmathspace" />
      <mrow>
        <mo>[</mo>
        <mrow>
          <mi>B</mi>
          <mo>&isin;</mo>
          <mi>P</mi>
          <mo lspace="veryverythickmathspace" rspace="veryverythickmathspace">&Longleftrightarrow;</mo>
          <mo rspace="0">&forall;</mo>
          <mi>C</mi>
          <mspace width="thinmathspace" />
          <mrow>
            <mo>(</mo>
            <mrow>
              <mi>C</mi>
              <mo>&isin;</mo>
              <mi>B</mi>
              <mo>&Implies;</mo>
              <mi>C</mi>
              <mo>&isin;</mo>
              <mi>A</mi>
            </mrow>
            <mo>)</mo>
          </mrow>
        </mrow>
        <mo>]</mo>
      </mrow>
    </mrow>
  </math>


- De Morgan's law:

  <math display="block">
  <mrow>
  <mtext>
  Logic:&nbsp;
  </mtext>
  <mo>&not;</mo>
  <mrow>
  <mo>(</mo>
  <mrow>
  <mi>p</mi>
  <mo>&and;</mo>
  <mi>q</mi>
  </mrow>
  <mo>)</mo>
  </mrow>
  <mo lspace="veryverythickmathspace" rspace="veryverythickmathspace">&Longleftrightarrow;</mo>
  <mrow>
  <mo>(</mo>
  <mrow>
  <mo>&not;</mo>
  <mi>p</mi>
  </mrow>
  <mo>)</mo>
  </mrow>
  <mo>&or;</mo>
  <mrow>
  <mo>(</mo>
  <mrow>
  <mo>&not;</mo>
  <mi>q</mi>
  </mrow>
  <mo>)</mo>
  </mrow>
  </mrow>
  </math>
  <math display="block">
  <mrow>
  <mtext>
  Boolean algebra:&nbsp;
  </mtext>
  <mover>
  <mrow>
  <munderover>
      <mo>&bigcup;</mo>
      <mrow>
  <mi>i</mi>
  <mo>=</mo>
  <mn>1</mn>
      </mrow>
      <mi>n</mi>
  </munderover>
  <msub>
      <mi>A</mi>
      <mi>i</mi>
  </msub>
  </mrow>
  <mo>&OverBar;</mo>
  </mover>
  <mo>=</mo>
  <munderover>
  <mo>&bigcap;</mo>
  <mrow>
  <mi>i</mi>
  <mo>=</mo>
  <mn>1</mn>
  </mrow>
  <mi>n</mi>
  </munderover>
  <mover accent="true">
  <msub>
  <mi>A</mi>
  <mi>i</mi>
  </msub>
  <mo>&OverBar;</mo>
  </mover>
  </mrow>
  </math>


- Quadratic formula:

  <math display="block">
    <mrow>
      <mi>x</mi>
      <mo>=</mo>
      <mfrac>
        <mrow>
          <mo form="prefix">&minus;</mo>
          <mi>b</mi>
          <mo>&PlusMinus;</mo>
          <msqrt>
            <msup>
              <mi>b</mi>
              <mn>2</mn>
            </msup>
            <mo>&minus;</mo>
            <mn>4</mn>
            <mo>&InvisibleTimes;</mo>
            <mi>a</mi>
            <mo>&InvisibleTimes;</mo>
            <mi>c</mi>
          </msqrt>
        </mrow>
        <mrow>
          <mn>2</mn>
          <mo>&InvisibleTimes;</mo>
          <mi>a</mi>
        </mrow>
      </mfrac>
    </mrow>
  </math>


- Binomial coefficient:

  <math display="block">
    <mrow>
      <mi>C</mi>
      <mrow>
        <mo>(</mo>
        <mi>n</mi>
        <mo>, </mo>
        <mi>k</mi>
        <mo>)</mo>
      </mrow>
      <mo>=</mo>
      <msubsup>
        <mi>C</mi>
        <mi>k</mi>
        <mi>n</mi>
      </msubsup>
      <mo>=</mo>
      <mmultiscripts>
        <mi>C</mi>
        <mi>k</mi>
        <none />
        <mprescripts />
        <mi>n</mi>
        <none />
      </mmultiscripts>
      <mo>=</mo>
      <mrow>
        <mo>(</mo>
        <mfrac linethickness="0">
          <mi>n</mi>
          <mi>k</mi>
        </mfrac>
        <mo>)</mo>
      </mrow>
      <mo>=</mo>
      <mfrac>
        <mrow>
          <mi>n</mi>
          <mo lspace="0">!</mo>
        </mrow>
        <mrow>
          <mi>k</mi>
          <mo lspace="0">!</mo>
          <mo rspace="mediummathspace">&InvisibleTimes;</mo>
          <mrow>
            <mo>(</mo>
            <mrow>
              <mi>n</mi>
              <mo>&minus;</mo>
              <mi>k</mi>
            </mrow>
            <mo>)</mo>
          </mrow>
          <mo lspace="0">!</mo>
        </mrow>
      </mfrac>
    </mrow>
  </math>


- Sophomore's law

  <math display="block">
    <mrow>
      <msubsup>
        <mo>&Integral;</mo>
        <mn>0</mn>
        <mn>1</mn>
      </msubsup>
      <msup>
        <mi>x</mi>
        <mi>x</mi>
      </msup>
      <mo rspace="mediummathspace">&InvisibleTimes;</mo>
      <mo rspace="0">&DifferentialD;</mo>
      <mi>x</mi>
      <mo>=</mo>
      <munderover>
        <mo>&Sum;</mo>
        <mrow>
          <mi>n</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mn>&infin;</mn>
      </munderover>
      <msup>
        <mrow>
          <mo>(</mo>
          <mrow>
            <mo form="prefix">&minus;</mo>
            <mn>1</mn>
          </mrow>
          <mo>)</mo>
        </mrow>
        <mrow>
          <mi>n</mi>
          <mo>+</mo>
          <mn>1</mn>
        </mrow>
      </msup>
      <mo>&InvisibleTimes;</mo>
      <msup>
        <mi>n</mi>
        <mrow>
          <mo form="prefix">&minus;</mo>
          <mi>n</mi>
        </mrow>
      </msup>
    </mrow>
  </math>


- Divergence

  <math display="block">
    <mrow>
      <mo>&nabla;</mo>
      <mo>&middot;</mo>
      <mover accent="true">
        <mi>v</mi>
        <mo class="smaller_font">&RightArrow;</mo>
      </mover>
      <mo>=</mo>
      <mfrac>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <msub>
            <mi>v</mi>
            <mi>x</mi>
          </msub>
        </mrow>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <mi>x</mi>
        </mrow>
      </mfrac>
      <mo>+</mo>
      <mfrac>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <msub>
            <mi>v</mi>
            <mi>y</mi>
          </msub>
        </mrow>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <mi>y</mi>
        </mrow>
      </mfrac>
      <mo>+</mo>
      <mfrac>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <msub>
            <mi>v</mi>
            <mi>z</mi>
          </msub>
        </mrow>
        <mrow>
          <mo rspace="0">&PartialD;</mo>
          <mi>z</mi>
        </mrow>
      </mfrac>
    </mrow>
  </math>

- Complex number

  <math display="block">
    <mrow>
      <mi>c</mi>
      <mo>=</mo>
      <mover>
        <mover>
          <mrow>
            <munder>
              <munder>
                <mrow>
                  <mspace width="1.1em" />
                  <mi>a</mi>
                  <mspace width="1.1em" />
                </mrow>
                <mo>&UnderBrace;</mo>
              </munder>
              <mtext>real</mtext>
            </munder>
            <mo>+</mo>
            <munder>
              <munder>
                <mrow>
                  <mspace width="1em" />
                  <mi>b</mi>
                  <mo lspace="0">&InvisibleTimes;</mo>
                  <mi>&ImaginaryI;</mi>
                  <mspace width="1em" />
                </mrow>
                <mo>&UnderBrace;</mo>
              </munder>
              <mtext>imaginary</mtext>
            </munder>
           </mrow>
          <mo>&OverBrace;</mo>
        </mover>
        <mtext>complex number</mtext>
      </mover>
    </mrow>
  </math>


- Moore determinant

  <math display="block">
    <mrow>
      <mi>M</mi>
      <mo>=</mo>
      <mrow>
        <mo>[</mo>
        <mtable>
          <mtr>
            <mtd>
              <msub>
                <mi>&alpha;</mi>
                <mn>1</mn>
              </msub>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mn>1</mn>
                <mi>q</mi>
              </msubsup>
            </mtd>
            <mtd>
              <mi>&hellip;</mi>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mn>1</mn>
                <mrow>
                  <msup>
                    <mi>q</mi>
                    <mrow>
                      <mi>n</mi>
                      <mo>&minus;</mo>
                      <mn>1</mn>
                    </mrow>
                  </msup>
                </mrow>
              </msubsup>
            </mtd>
          </mtr>
          <mtr>
            <mtd>
              <msub>
                <mi>&alpha;</mi>
                <mn>2</mn>
              </msub>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mn>2</mn>
                <mi>q</mi>
              </msubsup>
            </mtd>
            <mtd>
              <mi>&hellip;</mi>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mn>2</mn>
                <mrow>
                  <msup>
                    <mi>q</mi>
                    <mrow>
                      <mi>n</mi>
                      <mo>&minus;</mo>
                      <mn>1</mn>
                    </mrow>
                  </msup>
                </mrow>
              </msubsup>
            </mtd>
          </mtr>
          <mtr>
            <mtd>
              <mi>&vellip;</mi>
            </mtd>
            <mtd>
              <mi>&vellip;</mi>
            </mtd>
            <mtd>
              <mi>&dtdot;</mi>
            </mtd>
            <mtd>
              <mi>&vellip;</mi>
            </mtd>
          </mtr>
          <mtr>
            <mtd>
              <msub>
                <mi>&alpha;</mi>
                <mi>m</mi>
              </msub>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mi>m</mi>
                <mi>q</mi>
              </msubsup>
            </mtd>
            <mtd>
              <mi>&hellip;</mi>
            </mtd>
            <mtd>
              <msubsup>
                <mi>&alpha;</mi>
                <mi>m</mi>
                <mrow>
                  <msup>
                    <mi>q</mi>
                    <mrow>
                      <mi>n</mi>
                      <mo>&minus;</mo>
                      <mn>1</mn>
                    </mrow>
                  </msup>
                </mrow>
              </msubsup>
            </mtd>
          </mtr>
        </mtable>
        <mo>]</mo>
      </mrow>
    </mrow>
  </math>


- Sphere volume

  <span style="font-size: 8pt;">
    <span style="display: table; margin-left: auto; margin-right: auto; white-space: nowrap;
                 text-align: left; line-height: 0.75">
      &nbsp; &nbsp; Spherical coordinates derivation of the volume of a sphere
      <math style="font-size: xx-small">
        <mrow>
          <mo>(</mo>
          <mrow>
            <mfrac>
              <mn>4</mn>
              <mn>3</mn>
            </mfrac>
            <mo>&InvisibleTimes;</mo>
            <mi>&pi;</mi>
            <msup>
              <mi>R</mi>
              <mn>3</mn>
            </msup>
          </mrow>
          <mo>)</mo>
        </mrow>
      </math>
      .
      <br />
      The formula
      <math>
        <mi>S</mi>
      </math>
      for a sphere of radius
      <math>
        <mi>R</mi>
      </math>
      in spherical coordinates is:
      <br />
      <math>
        <mrow>
          <mi>S</mi>
          <mo>=</mo>
          <mrow>
            <mo>{</mo>
            <mrow>
              <mn>0</mn>
              <mo>&leq;</mo>
              <mi>&straightphi;</mi>
              <mo>&leq;</mo>
              <mn>2</mn>
              <mo>&InvisibleTimes;</mo>
              <mi>&pi;</mi>
            </mrow>
            <mo>,&nbsp;</mo>
            <mrow>
              <mn>0</mn>
              <mo>&leq;</mo>
              <mi>&theta;</mi>
              <mo>&leq;</mo>
              <mi>&pi;</mi>
            </mrow>
            <mo>,&nbsp; </mo>
            <mrow>
              <mn>0</mn>
              <mo>&leq;</mo>
              <mi>&rho;</mi>
              <mo>&leq;</mo>
              <mi>R</mi>
            </mrow>
            <mo>}</mo>
          </mrow>
        </mrow>
      </math>
    </span>
    <math display="block">
      <mtable displaystyle="true" class="thin_column_padding" columnalign="right left">
        <mtr>
          <mtd>
<mrow>
	<mtext>Volume</mtext>
	    </mrow>
          </mtd>
          <mtd>
            <mrow>
              <mo>=</mo>
              <munder>
                <mo>&iiint;</mo>
                <mi>S</mi>
              </munder>
              <msup>
                <mi>&rho;</mi>
                <mn>2</mn>
              </msup>
              <mo>&InvisibleTimes;</mo>
              <mo>sin</mo>
              <mo rspace="thinmathspace">&ApplyFunction;</mo>
              <mi>&theta;</mi>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&rho;</mi>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&theta;</mi>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&straightphi;</mi>
            </mrow>
          </mtd>
        </mtr>
        <mtr>
          <mtd />
          <mtd>
            <mrow>
              <mo>=</mo>
              <msubsup>
                <mo>&Integral;</mo>
                <mrow>
                <mspace width="verythinmathspace" />
                <mn>0</mn>
                </mrow>
                <mrow>
                  <mn>2</mn>
                  <mo>&InvisibleTimes;</mo>
                  <mi>&pi;</mi>
                </mrow>
              </msubsup>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&straightphi;</mi>
              <mo lspace="thickmathspace">&InvisibleTimes;</mo>
              <msubsup>
                <mo>&Integral;</mo>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>0</mn>
                </mrow>
                <mi>&pi;</mi>
              </msubsup>
              <mo>sin</mo>
              <mo rspace="thinmathspace">&ApplyFunction;</mo>
              <mi>&theta;</mi>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&theta;</mi>
              <mo lspace="thickmathspace">&InvisibleTimes;</mo>
              <msubsup>
                <mo>&Integral;</mo>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>0</mn>
                </mrow>
                <mi>R</mi>
              </msubsup>
              <msup>
                <mi>&rho;</mi>
                <mn>2</mn>
              </msup>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mo rspace="0">&DifferentialD;</mo>
              <mi>&rho;</mi>
            </mrow>
          </mtd>
        </mtr>
        <mtr>
          <mtd />
          <mtd>
            <mrow>
              <mo>=</mo>
              <mspace width="mediummathspace" />
              <mi>&straightphi;</mi>
              <mspace width="verythinmathspace" />
              <msubsup>
                <mo>&vert;</mo>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>0</mn>
                </mrow>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>2</mn>
                  <mo>&InvisibleTimes;</mo>
                  <mi>&pi;</mi>
                </mrow>
              </msubsup>
              <mo rspace="mediummathspace">&InvisibleTimes;</mo>
              <mrow>
                <mo>(</mo>
                <mrow>
                  <mo form="prefix">&minus;</mo>
                  <mi>cos</mi>
                  <mo rspace="thinmathspace">&ApplyFunction;</mo>
                  <mi>&theta;</mi>
                </mrow>
                <mo>)</mo>
              </mrow>
              <mspace width="verythinmathspace" />
              <msubsup>
                <mo>&vert;</mo>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>0</mn>
                </mrow>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mi>&pi;</mi>
                </mrow>
              </msubsup>
              <mspace width="veryverythickmathspace" />
              <mo>&InvisibleTimes;</mo>
              <mfrac>
                <mn>1</mn>
                <mn>3</mn>
              </mfrac>
              <mo>&InvisibleTimes;</mo>
              <msup>
                <mi>&rho;</mi>
                <mn>3</mn>
              </msup>
              <mspace width="verythinmathspace" />
              <msubsup>
                <mo>&vert;</mo>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mn>0</mn>
                </mrow>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mi>R</mi>
                </mrow>
              </msubsup>
            </mrow>
          </mtd>
        </mtr>
        <mtr>
          <mtd />
          <mtd>
            <mrow>
              <mo>=</mo>
              <mspace width="mediummathspace" />
              <mn>2</mn>
              <mo>&InvisibleTimes;</mo>
              <mi>&pi;</mi>
              <mo lspace="thickmathspace" rspace="thickmathspace">&times;</mo>
              <mn>2</mn>
              <mo lspace="thickmathspace" rspace="thickmathspace">&times;</mo>
              <mfrac>
                <mn>1</mn>
                <mn>3</mn>
              </mfrac>
              <mo>&InvisibleTimes;</mo>
              <msup>
                <mi>R</mi>
                <mn>3</mn>
              </msup>
            </mrow>
          </mtd>
        </mtr>
        <mtr>
          <mtd />
          <mtd>
            <mrow>
              <mo>=</mo>
              <mspace width="mediummathspace" />
              <mfrac>
                <mn>4</mn>
                <mn>3</mn>
              </mfrac>
              <mo>&InvisibleTimes;</mo>
              <mi>&pi;</mi>
              <msup>
                <mi>R</mi>
                <mn>3</mn>
              </msup>
            </mrow>
          </mtd>
        </mtr>
      </mtable>
    </math>
  </span>


- Schwinger-Dyson equation

  <math style="font-size: 9pt" display="block">
    <mrow>
      <mrow>
        <mo>&lang;</mo>
        <mrow>
          <mi>&psi;</mi>
          <mspace width="thinmathspace" />
          <mrow>
            <mo>|</mo>
            <mrow>
              <mspace width="thinmathspace" />
              <mi>&Tscr;</mi>
              <mrow>
                <mo>{</mo>
                <mrow>
                  <mfrac>
                    <mi>&delta;</mi>
                    <mrow>
                      <mi>&delta;</mi>
                      <mi>&straightphi;</mi>
                    </mrow>
                  </mfrac>
                  <mi>F</mi>
                  <mo>&ApplyFunction;</mo>
                  <mrow>
                    <mo>[</mo>
                    <mi>&straightphi;</mi>
                    <mo>]</mo>
                  </mrow>
                </mrow>
                <mo>}</mo>
              </mrow>
            </mrow>
            <mo>|</mo>
          </mrow>
          <mspace width="thinmathspace" />
          <mi>&psi;</mi>
        </mrow>
        <mo>&rang;</mo>
      </mrow>
      <mo>=</mo>
      <mo form="prefix">&minus;</mo>
      <mi>&ImaginaryI;</mi>
      <mo>&InvisibleTimes;</mo>
      <mrow>
        <mo>&lang;</mo>
        <mrow>
          <mi>&psi;</mi>
          <mspace width="thinmathspace" />
          <mrow>
            <mo>|</mo>
            <mrow>
              <mspace width="thinmathspace" />
              <mi>&Tscr;</mi>
              <mrow>
                <mo>{</mo>
                <mrow>
                  <mi>F</mi>
                  <mo>&ApplyFunction;</mo>
                  <mrow>
                    <mo>[</mo>
                    <mi>&straightphi;</mi>
                    <mo>]</mo>
                  </mrow>
                  <mo>&InvisibleTimes;</mo>
                  <mfrac>
                    <mi>&delta;</mi>
                    <mrow>
                      <mi>&delta;</mi>
                      <mi>&straightphi;</mi>
                    </mrow>
                  </mfrac>
                  <mi>S</mi>
                  <mo>&ApplyFunction;</mo>
                  <mrow>
                    <mo>[</mo>
                    <mi>&straightphi;</mi>
                    <mo>]</mo>
                  </mrow>
                  <mo>}</mo>
                </mrow>
                <mo>|</mo>
              </mrow>
            </mrow>
          </mrow>
          <mspace width="thinmathspace" />
          <mi>&psi;</mi>
        </mrow>
        <mo>&rang;</mo>
      </mrow>
    </mrow>
  </math>


- Differentiable manifold (tangent vector)

  <math style="font-size: 9pt" display="block">
    <mrow>
      <msub>
        <mi>&gamma;</mi>
        <mn>1</mn>
      </msub>
      <mo>&equiv;</mo>
      <msub>
        <mi>&gamma;</mi>
        <mn>2</mn>
      </msub>
      <mo lspace="veryverythickmathspace" rspace="veryverythickmathspace">&Longleftrightarrow;</mo>
      <mrow>
        <mo>{</mo>
        <mtable class="thin_column_padding" columnalign="left">
          <mtr>
            <mtd>
              <msub>
                <mi>&gamma;</mi>
                <mn>1</mn>
              </msub>
              <mo>&ApplyFunction;</mo>
              <mrow>
                <mo>(</mo>
                <mn>0</mn>
                <mo>)</mo>
              </mrow>
              <mo>=</mo>
              <msub>
                <mi>&gamma;</mi>
                <mn>2</mn>
              </msub>
              <mo>&ApplyFunction;</mo>
              <mrow>
                <mo>(</mo>
                <mn>0</mn>
                <mo>)</mo>
              </mrow>
              <mo>=</mo>
              <mi>p</mi>
              <mtext>, and</mtext>
            </mtd>
          </mtr>
          <mtr>
            <mtd>
              <msub>
                <mrow>
                  <mrow>
                    <mfrac>
                      <mo>&DifferentialD;</mo>
                      <mrow>
                        <mo rspace="0">&DifferentialD;</mo>
                        <mi>t</mi>
                      </mrow>
                    </mfrac>
                    <mo>&ApplyFunction;</mo>
                    <mi>&straightphi;</mi>
                    <mo>&compfn;</mo>
                    <msub>
                      <mi>&gamma;</mi>
                      <mn>1</mn>
                    </msub>
                    <mo>&ApplyFunction;</mo>
                    <mrow>
                      <mo>(</mo>
                      <mi>t</mi>
                      <mo>)</mo>
                    </mrow>
                    <mspace width="verythinmathspace" />
                  </mrow>
                  <mo>|</mo>
                </mrow>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mi>t</mi>
                  <mo>=</mo>
                  <mn>0</mn>
                </mrow>
              </msub>
              <mo>=</mo>
              <msub>
                <mrow>
                  <mrow>
                    <mfrac>
                      <mo>&DifferentialD;</mo>
                      <mrow>
                        <mo rspace="0">&DifferentialD;</mo>
                        <mi>t</mi>
                      </mrow>
                    </mfrac>
                    <mo>&ApplyFunction;</mo>
                    <mi>&straightphi;</mi>
                    <mo>&compfn;</mo>
                    <msub>
                      <mi>&gamma;</mi>
                      <mn>2</mn>
                    </msub>
                    <mo>&ApplyFunction;</mo>
                    <mrow>
                      <mo>(</mo>
                      <mi>t</mi>
                      <mo>)</mo>
                    </mrow>
                    <mspace width="verythinmathspace" />
                  </mrow>
                  <mo>|</mo>
                </mrow>
                <mrow>
                  <mspace width="verythinmathspace" />
                  <mi>t</mi>
                  <mo>=</mo>
                  <mn>0</mn>
                </mrow>
              </msub>
            </mtd>
          </mtr>
        </mtable>
      </mrow>
    </mrow>
  </math>


- Cichoń's diagram

  <math style="font-size: 7pt;" display="block">
    <mrow>
      <mtable class="thin_column_padding center_column_content">
        <mtr>
          <mtd columnspan="2" />
          <mtd>
            <mo>cov</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Lscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>non</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Kscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>cof</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Kscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>cof</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Lscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <msup>
              <mn>2</mn>
              <msub>
                <mi>&aleph;</mi>
                <mn>0</mn>
              </msub>
            </msup>
          </mtd>
        </mtr>
        <mtr>
          <mtd columnspan="2" />
          <mtd rowspan="3">
            <mo minsize="4.7em">&uparrow;</mo> <!-- minsize HACK for Firefox bug 236963 -->
          </mtd>
          <mtd />
          <mtd>
            <mo>&uparrow;</mo>
          </mtd>
          <mtd />
          <mtd>
            <mo>&uparrow;</mo>
          </mtd>
          <mtd />
          <mtd rowspan="3">
            <mo minsize="4.7em">&uparrow;</mo> <!-- minsize HACK for Firefox bug 236963 -->
          </mtd>
          <mtd columnspan="2" />
        </mtr>
        <mtr>
          <mtd columnspan="4" />
          <mtd>
            <mi>&bfr;</mi>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mi>&dfr;</mi>
          </mtd>
          <mtd columnspan="5" />
        </mtr>
        <mtr>
          <mtd columnspan="4" />
          <mtd>
            <mo>&uparrow;</mo>
          </mtd>
          <mtd />
          <mtd>
            <mo>&uparrow;</mo>
          </mtd>
          <mtd columnspan="5" />
        </mtr>
        <mtr>
          <mtd>
            <msub>
              <mi>&aleph;</mi>
              <mn>1</mn>
            </msub>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>add</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Lscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd >
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>add</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Kscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>cov</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Kscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd>
            <mo>&longrightarrow;</mo>
          </mtd>
          <mtd>
            <mo>non</mo>
            <mrow>
              <mo>(</mo>
              <mi>&Lscr;</mi>
              <mo>)</mo>
            </mrow>
          </mtd>
          <mtd columnspan="2" />
        </mtr>
      </mtable>
    </mrow>
  </math>


- Multiscripts & Greek alphabet

  <math style="font-size: 24pt" display="block">
    <mrow>
      <munderover>
        <mmultiscripts>
          <mo>&Product;</mo>
          <mmultiscripts>
            <mi>&Efr;</mi>
            <mi>&upsilon;</mi>
            <mi>&tau;</mi>
            <mprescripts />
            <mi>&rho;</mi>
            <mi>&sigma;</mi>
          </mmultiscripts>
          <mmultiscripts>
            <mi>&Dfr;</mi>
            <mi>&pi;</mi>
            <mi>&omicron;</mi>
            <mprescripts />
            <mi>&nu;</mi>
            <mi>&xi;</mi>
          </mmultiscripts>
          <mprescripts />
          <mmultiscripts>
            <mi>&Afr;</mi>
            <mi>&delta;</mi>
            <mi>&gamma;</mi>
            <mprescripts />
            <mi>&alpha;</mi>
            <mi>&beta;</mi>
          </mmultiscripts>
          <mmultiscripts>
            <mi>&Bfr;</mi>
            <mi>&theta;</mi>
            <mi>&eta;</mi>
            <mprescripts />
            <mi>&epsilon;</mi>
            <mi>&zeta;</mi>
          </mmultiscripts>
        </mmultiscripts>
        <mmultiscripts>
          <mi>&Ffr;</mi>
          <mi>&omega;</mi>
          <mi>&psi;</mi>
          <mprescripts />
          <mi>&straightphi;</mi>
          <mi>&chi;</mi>
        </mmultiscripts>
        <mmultiscripts>
          <mi>&Cfr;</mi>
          <mi>&mu;</mi>
          <mi>&lambda;</mi>
          <mprescripts />
          <mi>&iota;</mi>
          <mi>&kappa;</mi>
        </mmultiscripts>
      </munderover>
    </mrow>
  </math>


- Nested roots

  <math style="font-size: 8pt" display="block">
    <mrow>
      <mfrac>
        <msqrt>
          <mn>1</mn>
          <mo>+</mo>
          <mroot>
            <mrow>
              <mn>2</mn>
              <mo>+</mo>
              <mroot>
                <mrow>
                  <mn>3</mn>
                  <mo>+</mo>
                  <mroot>
                    <mrow>
                      <mn>4</mn>
                      <mo>+</mo>
                      <mroot>
                        <mrow>
                          <mn>5</mn>
                          <mo>+</mo>
                          <mroot>
                            <mrow>
                              <mn>6</mn>
                              <mo>+</mo>
                              <mroot>
                                <mrow>
                                  <mn>7</mn>
                                  <mo>+</mo>
                                  <mroot>
                                    <mi>A</mi>
                                    <mn>19</mn>
                                  </mroot>
                                </mrow>
                                <mn>17</mn>
                              </mroot>
                            </mrow>
                            <mn>13</mn>
                          </mroot>
                        </mrow>
                        <mn>11</mn>
                      </mroot>
                    </mrow>
                    <mn>7</mn>
                  </mroot>
                </mrow>
                <mn>5</mn>
              </mroot>
            </mrow>
            <mn>3</mn>
          </mroot>
        </msqrt>
        <msup>
          <mi>&exponentiale;</mi>
          <mi>&pi;</mi>
        </msup>
      </mfrac>
      <mo>=</mo>
      <msup>
        <mi>x</mi>
        <mo>&tprime;</mo>
      </msup>
    </mrow>
  </math>


- Nested matrices

  <math display="block">
    <mrow>
      <mrow>
        <mo>(</mo>
        <mtable class="no_column_padding center_column_content">
          <mtr>
            <mtd>
              <mrow>
                <mo>(</mo>
                <mtable>
                  <mtr>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>1</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>2</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>3</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>4</mn>
                      </msub>
                    </mtd>
                  </mtr>
                  <mtr>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>5</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>6</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>7</mn>
                      </msub>
                    </mtd>
                    <mtd>
                      <msub>
                        <mi>a</mi>
                        <mn>8</mn>
                      </msub>
                    </mtd>
                  </mtr>
                </mtable>
                <mo>)</mo>
              </mrow>
            </mtd>
            <mtd rowspan="2">
              <mrow>
                <mo>(</mo>
                <mtable class="thin_column_padding">
                  <mtr>
                    <mtd>
                      <msub>
                        <mi>b</mi>
                        <mn>1</mn>
                      </msub>
                    </mtd>
                  </mtr>
                  <mtr>
                    <mtd>
                      <msub>
                        <mi>b</mi>
                        <mn>2</mn>
                      </msub>
                    </mtd>
                  </mtr>
                  <mtr>
                    <mtd>
                      <mspace height="1.4em" />
                      <msub>
                        <mi>b</mi>
                        <mn>3</mn>
                      </msub>
                    </mtd>
                  </mtr>
                  <mtr>
                    <mtd>
                      <msub>
                        <mi>b</mi>
                        <mn>4</mn>
                      </msub>
                    </mtd>
                  </mtr>
                </mtable>
                <mo>)</mo>
              </mrow>
            </mtd>
          </mtr>
          <mtr>
            <mtd>
              <mtable class="center_column_content">
                <mtr>
                  <mtd>
                    <mi>&emsp;</mi>
                    <mi>&emsp;</mi>
                    <mn style="font-size: 150%">0</mn>
                    <mi>&ensp;</mi>
                  </mtd>
                  <mtd>
                    <mrow>
                      <mo>(</mo>
                      <mtable>
                        <mtr>
                          <mtd>
                            <msub>
                              <mi>c</mi>
                              <mn>1</mn>
                            </msub>
                          </mtd>
                          <mtd>
                            <msub>
                              <mi>c</mi>
                              <mn>2</mn>
                            </msub>
                          </mtd>
                        </mtr>
                        <mtr>
                          <mtd>
                            <msub>
                              <mi>c</mi>
                              <mn>3</mn>
                            </msub>
                          </mtd>
                          <mtd>
                            <msub>
                              <mi>c</mi>
                              <mn>4</mn>
                            </msub>
                          </mtd>
                        </mtr>
                      </mtable>
                      <mo>)</mo>
                    </mrow>
                  </mtd>
                </mtr>
              </mtable>
            </mtd>
            <mtd />
          </mtr>
        </mtable>
        <mo>)</mo>
      </mrow>
    </mrow>
  </math>


- font sizes

  <math display="block">
    <mrow>
      <mtext>scriptlevel : </mtext>
      <mstyle scriptlevel="-3">
        <mo form="prefix">&minus;</mo>
        <mn>3</mn>
      </mstyle>
      <mo>,&nbsp;</mo>
      <mstyle scriptlevel="-2">
        <mo form="prefix">&minus;</mo>
        <mn>2</mn>
      </mstyle>
      <mo>,&nbsp;</mo>
      <mstyle scriptlevel="-1">
        <mo form="prefix">&minus;</mo>
        <mn>1</mn>
      </mstyle>
      <mo>,&nbsp;</mo>
      <mstyle scriptlevel="0">
        <mn>0</mn>
      </mstyle>
      <mo>,&nbsp;</mo>
      <mstyle scriptlevel="1">
        <mn>1</mn>
      </mstyle>
    </mrow>
  </math>

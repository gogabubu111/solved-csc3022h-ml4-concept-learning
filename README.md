Download Link: https://assignmentchef.com/product/solved-csc3022h-ml4-concept-learning
<br>
Implement (in C++) the Candidate Elimination algorithm (chapter 2 of [Mitchell, 1997]). Use the training examples in table 1 to verify that it correctly produces the following hypothesis for learning concept <em>Japanese</em> <em>Economy</em> <em>Car</em> (lecture 3):

<em>&lt;</em> <em>Japan,</em> ?<em>,</em> ?<em>,</em> ?<em>,</em> <em>Economy</em> <em>&gt; </em><strong>Q1:</strong> Now change the training examples given in table 1 so as the candidate elimination algorithm learns the following hypothesis:

<em>&lt;</em> <em>Japan,</em> ?<em>,</em> ?<em>,</em> ?<em>,</em> <em>Sports</em> <em>&gt;</em>

<strong>Q2:</strong> What is the minimum number of training examples to learn this concept (<em>Japanese</em> <em>Sports</em> <em>Car</em>)?

In a ZIP file, place the source code, executable, and a text file containing your list of training examples (answers to Q1 and Q2). Upload ZIP file to the open assignment on <em>Vula</em>.

1

Table 1: Training examples for target concept <em>Japanese Economy Car</em>.

<table width="427">

 <tbody>

  <tr>

   <td width="58"><strong>Origin</strong></td>

   <td width="107"><strong>Manufacturer</strong></td>

   <td width="61"><strong>Colour</strong></td>

   <td width="64"><strong>Decade</strong></td>

   <td width="69"><strong>Type</strong></td>

   <td width="66"><strong>Label</strong></td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Honda</td>

   <td width="61">Blue</td>

   <td width="64">1980</td>

   <td width="69">Economy</td>

   <td width="66">Positive</td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Toyota</td>

   <td width="61">Green</td>

   <td width="64">1970</td>

   <td width="69">Sports</td>

   <td width="66">Negative</td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Toyota</td>

   <td width="61">Blue</td>

   <td width="64">1990</td>

   <td width="69">Economy</td>

   <td width="66">Positive</td>

  </tr>

  <tr>

   <td width="58">USA</td>

   <td width="107">Chrysler</td>

   <td width="61">Red</td>

   <td width="64">1980</td>

   <td width="69">Economy</td>

   <td width="66">Negative</td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Honda</td>

   <td width="61">White</td>

   <td width="64">1980</td>

   <td width="69">Economy</td>

   <td width="66">Positive</td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Toyota</td>

   <td width="61">Green</td>

   <td width="64">1980</td>

   <td width="69">Economy</td>

   <td width="66">Positive</td>

  </tr>

  <tr>

   <td width="58">Japan</td>

   <td width="107">Honda</td>

   <td width="61">Red</td>

   <td width="64">1990</td>

   <td width="69">Economy</td>

   <td width="66">Negative</td>

  </tr>

 </tbody>

</table>

<strong>References</strong>

[Mitchell, 1997] Mitchell, T. (1997). <em>Machine Learning</em>. McGraw Hill, New York, USA.
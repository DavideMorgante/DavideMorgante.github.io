---
title: "Tutorato Metodi Matematici della Fisica"
collection: teaching
type: "Laurea Triennale"
permalink: /teaching/MM24
venue: "Unimi, Fisica"
date: 2024-03-06
year: 2023/2024
location: "Milano, Italia"
header-includes: 
  - \usepackage{tikz}
  - \usepackage{pgfplots}
  - \usetikzlibrary{calc}
output:
    pdf_document
---
{% include text-expand.html %}

<span style="color:red">Important announcement: On Monday 24th we are going to give the solutions to the exam of 20/06/2024</span>

Here you can find the various notes of the lectures with the exercises presented during the lessons plus some other exercises that I didn't have time to do in class. Most of the notes come with some basic theory behind the exercises themselves.

The lectures are held in presence in the following days

| Day      | Time     | Classroom |
| -------- | -------- | --------- |
| Monday   | 16.30-18 | Aula D    |
| Thursday | 16.30-18 | Aula I    |

I strongly recommend to follow the lectures in class so that you can ask me any question directly. For any other questions related to exercises, done and not done during the lecture, you can contact Me or Andrea Barontini at the following e-mail addresses

* Davide Morgante: davide.morgante@mi.infn.it
* Andrea Barontini: andrea.barontini@unimi.it

We organized also the following *office hours*, where the students can come and ask us questions

| Day       | Time        | Office          |
| --------- | ----------- | --------------- |
| Wednesday | 10.30-11.30 | LITA - BO.DO 06 |

Before coming to the office hours, please send us an e-mail to know. If you need to come outside office hours, send me (Davide) and e-mail and we can organize something 

My office, DC/T/37, is located at the ground floor, at the end of the central corridor to the left, near the bathrooms (the office is two doors from prof. Molinari's office).

Andrea's office, BO.DO 06, is located at the 2nd floor of the LITA building same corridor of Aula Polvani.

<section class="accordion">
  <input type="checkbox" name="collapse" id="handle1">
    <par class="handle">
      <label for="handle1"> Here is a list of my favorite books, the more mathematical one are highlighted in red  </label>
    </par>
  <div class="content">
  <ol>
    <li> Complex Analysis: </li>
    <ul>
      <li> <span style="color:red">Functional Theory of One Complex Variable</span> - Greene, Krantz </li>
      <li> <span style="color:red">Complex Analysis</span> - Ahlfors </li>
      <li> Elementi di Analisi Complessa - Presilla (Con moltissimi esercizi svolti) </li>
      <li> <span style="color:red">Algebraic Curves and Riemann Surfaces</span> - Miranda </li>
    </ul>
    <li> General Mathematical Methods: </li>
    <ul>
      <li> Mathematics of Classical and Quantum Physics - Byron, Fuller </li>
      <li> Mathematical Methods for Students of Physics and Related Fields - Hassani </li>
      <li> Mathematical Methods for Physics and Engineering - Riley, Hobson, Bence </li>
      <li> <a href="https://www.ge.infn.it/~zanghi/metodi/ZUL.pdf"> Appunti di Metodi Matematici della Fisica </a> - Zanghì </li>
      <li> Metodi Matematici della Fisica - Cicogna </li>
      <li> A Guide to Mathematical Methods for Physicists - Petrini, Pradisi, Zaffaroni </li>
    </ul>
    <li> Differential Equations: </li>
    <ul>
      <li> Ordinary Differential Equations - Arnol'd </li>
      <li> Differential Equations, Dynamical Systems, and an Introduction to Chaos - Hirsch, Smale, Devaney </li>
    </ul>
    <li> Operators, Distributions and Functional Analysis: </li>
    <ul>
      <li> <a href="https://www.roma1.infn.it/~cesi/rudimenti/RAID-s-v03.pdf"> Rudimenti di Analisi Infinito Dimensionale </a> - Cesi </li>
      <li> <span style="color:red">Distributions and Operators</span> - Grubb </li>
    </ul>
  </ol>
  </div>
</section>

## Lecture 1: Complex differentiability, Holomorphic functions, Harmonic functions

### 18/03/24
You can find the pdf of the lesson by Andrea from [this link](http://DavideMorgante.github.io/files/Lezione1.pdf).
Next lecture we are going to do similar exercises for the students that couldn't follow this lesson due to the laboratory course.

### 21/03/24
You can find the pdf of my lesson at [this link](http://DavideMorgante.github.io/files/Lezione1_3.pdf). The exercise of the differential equation can be found [here](http://DavideMorgante.github.io/files/Lezione1_2.pdf).

## Lecture 2: Line integrals in the complex plane

### 25/03/24
You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Integrali_1.pdf). The last exercise we didn't do in class.

### 04/04/24
Andrea did the same exercises of the previous link plus the first one that you can find from [this link](http://DavideMorgante.github.io/files/Metodi23/5-04-23_Frigerio.pdf). Here you can find a couple more exercises from last year.

## Lecture 3: Taylor and Laurent series, Radius of convergence, Cayley-Hamilton theorem for the power of a matrix (8-11/04/24)

In the following weeks we are going to study in great details the properties of power expansions for holomorphic and meromorphic functions. This is a very relevant topic of this course, so I recommend coming to the tutoring classes. 

You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione2.pdf). **Please Note:** There is an error in the solution of the Cayley-Hamilton exercise. You can find the right solution from [this link](http://DavideMorgante.github.io/files/CH_corretto.pdf).

Here you can find some [notes on Cayley-Hamilton theorem](https://web.mit.edu/2.151/www/Handouts/CayleyHamilton.pdf).

## Lecture 4: Taylor and Laurent series, Radius of convergence, Cayley-Hamilton theorem for the power of a matrix (18-22/04/24)

You can find the pdf of this lecture from [this link](../files/Laurent_18.pdf). We also solved the exercise I left for homework of the laurent expansion of $\mathrm{log}(-z)/(z^2-1)^2$. Next Monday Andrea will do the same exercises. 

For the ones of you that never saw the Riemann surface of multi-valued functions, I really advise you to watch this [short video series](https://www.youtube.com/playlist?list=PLiaHhY2iBX9g6KIvZ_703G3KJXapKkNaF) on complex functions which I find really instructive. 

## Lectures 5: Residue Theorem, Cauchy Principal Value, Order k poles and their residues, Integrals with branch cuts 

### 29/04/24

You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione4.pdf). Also, if you want you can check out this very interesting [youtube video](https://youtu.be/5RHSS-zMaAQ?si=QXOZS3OBUWbR5zsT) which explains in a very simple fashion the very deep connection between complex analysis and algebraic geometry. This topic is a very relevant one in theoretical physics, in particular for the analysis of [certain theories of particles](https://en.wikipedia.org/wiki/Supersymmetry) where exact solutions are known thanks to [Seiber-Witten theory](https://en.wikipedia.org/wiki/Seiberg%E2%80%93Witten_theory). Their work paved the ground to a deeper understanding of [electro-magnetic duality](https://en.wikipedia.org/wiki/Montonen%E2%80%93Olive_duality).

### Andrea - 06/05/24

You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione6.pdf). Andrea is going to do these exercises on next monday. 

### 09/05/24

You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione4.pdf). Some of you had problems with the contribution from the poles in the first exercise. The function we needed to compute was 

$$ \int_0^\infty \frac{\sqrt{x}}{x^2-16}\mathrm{d}x $$

The contour integral we choose had two semicircular paths around the pole at $z=4$ and we found the value of the integral, in the limit of $r\rightarrow 0$ with the residue at the pole. This might seem confusing since the residue theorem is valid for closed paths containing some poles, while these two were not closed. The result in fact is a consequence of the [*small circle* lemma](https://it.wikipedia.org/wiki/Lemma_del_cerchio_piccolo) (The second lemma in the Wikipedia page), i.e. is a consequence of the behaviour of the function near the pole when we take the contour to be small. I'm sorry if I wasn't clear that it has "nothing" (sort of) to do with the residue theorem. 

### Andrea - 23/05/2024
The exercises done by Andrea can be found in the last link.

## Lecture 5: Finite dimensional Hilbert Spaces and Operators acting on such Hilbert spaces 

### 13/05/24
You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione9.pdf). We had time to do only the first exercise.

### Andrea - 20/05/24
The exercises done by Andrea can be found in the last link.

## Lecture 6: Operators on finite dimensional Hilbert spaces, Group theory and Lie Groups

### 27/05/2024 and 30/05/2024
You can find the pdf with the exercises [here](http://DavideMorgante.github.io/files/Lezione10.pdf). There is a lot to say about groups, algebras and their representation. In the lecture I've tried to give you some basics about it but they are not really needed to do the exercises. For the curious amongts you, I leve here some links

  - [Definition of groups](https://en.wikipedia.org/wiki/Group_(mathematics)): we mainly talked about continuous groups, in particular we looked at $\mathrm{SO}(n)$, the special [orthogonal group](https://en.wikipedia.org/wiki/Orthogonal_group), which describes rotations in $\mathbb{R}^n$ and $\mathrm{U}(n)$, the [unitary group](https://en.wikipedia.org/wiki/Unitary_group), which describes rotations in $\mathbb{C}^n$. The group $\mathrm{SU}(2)$ is of particular interes in physics since it describes the behaviour of spin. These are also cases of [Lie groups](https://en.wikipedia.org/wiki/Lie_group), special groups which are also finite-dimensional smooth manifolds. 
  - [Group representations](https://en.wikipedia.org/wiki/Group_representation): this tell us how to describe elements of groups by matrices. 
  - [Lie algebras and generators](https://en.wikipedia.org/wiki/Lie_algebra#Generators_and_dimension): Lie groups are so special that all we need to know to describe them is their behaviour near the identity element, which is described by the tangent space at the identity. This space is the Lie algebra and the basis elements for this vector space are called generators. Lie algebras and Lie groups are connected by the [exponential map](https://en.wikipedia.org/wiki/Exponential_map_(Lie_theory)).


## Lecture 7: Infinite dimensional, separable, Hilbert spaces and Operators on them (23/05/2022)

### 13/06/24
You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione11.pdf).

## Lecture 8: Tempered Distributions (09/06/2022)

### 17/06/24
Upon request of the students we did some exercises on distributions. You can find the pdf of the lesson from [this link](http://DavideMorgante.github.io/files/Lezione15.pdf).

## Last lecture: Exam 20/06/2024 (24/06/2024)
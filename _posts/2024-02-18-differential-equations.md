---
layout: post
title: Differential Equations I
category: Mathematics
---

## Introduction
>The *differential* and *equation* suggest solving some kind of equation that contains derivatives $y'$, $y''$
> Solving differential equations such as $y'' + 2y' + y = 0$ for unknown fuction $y = \phi\left(x\right)$.

# Chapter 1

## 1.1 Definitions and Terminology

#### Definition 1.1.1
>**Differential Equation**\
>An equation containing the derivatives for one or more unknown fucntions (or dependent variable), with respect to one or more independent variables, is said to be a **differential equation (DE)**


### Classification by Type
If a differential equation contains only ordinary derivatives of one or more unknown fucntions with resprect to a single independent variable, it is said to be an **ordinary differential equation (ODE)**.
> Example 1.1.1
> 
> $$\frac{dy}{dx} + y = e^{x}$$


If an equation involving partial derivatives of one or more unknown functions of two or more independent variables is a **partial differential equation (PDE)**.
> Example 1.1.2
> 
> $$\frac{\partial^2 y}{\partial x^2} + y = 0$$

### Classification by Order
The order of a differential eqaution is the order of the highest derivative in the equation.
> Examlple 1.1.3
> 
> $$\frac{dy}{dx} + y = e^{x}$$

The order of above equation is one.

> **Differential Form**
>
>$$M(x,y)dx + N(x,y)dy = 0$$

### Classification by Linearity
An nth-order oridinary differential equation is called to be linear if *F* is linear in $y,y',...,y^{(n)}$. This means that an nth-order ODE is linear when is

$$ a_n(x)y^{(n)}+a_{n-1}(x)y^{(n-1)} + ... +a_1(x)y'+a_0(x)y - g(x) = 0$$


> Examlple 1.1.4\
> Linear
> 
> $$y'' -2y' + y = 0$$
> 
> Nonlinear
> 
> $$(1-y)y' +2y = e^{x}$$


### Solutions
#### Solution of an ODE
>Any function,  $\phi$ defined on an interval I and possessing at least n derivatives that are continuous on I, which when substituted into an -order ordinary differential equation reduces the equation to an identity, is said to be a solution of the equation on the interval.
In other words, a solution of an nth-order oridinary differential equation is simply a form of

$$y = f{(x)}$$ 

or

$$f(x,y) = C $$ 
---
layout: post
title: "Simple Made Easy"
categories: reference
---

[Talk](http://www.slideshare.net/evandrix/simple-made-easy)

Abstraction Questions
---------------------

- Who - Build from subcomponents that don't rely on each other
- What - Don't complect with How by jamming an interface with implementation
- When, Where - two components should communicate via a queue instead of directly
- Why - Business logic
- How - Do the work

<table class="table">
    <thead>
        <tr><th>Complexity</th><th>Simplicity</th></tr>
    </thead>
    <tbody>
        <tr><td>State, Objects</td><td>Values</td></tr>
        <tr><td>Methods</td><td>Functions, Namespaces</td></tr>
        <tr><td>vars</td><td>Managed refs</td></tr>
        <tr><td>Inheritance, switch, matching</td><td>Polymorphism a la carte</td></tr>
        <tr><td>Syntax</td><td>Data</td></tr>
        <tr><td>Imperative loops, fold</td><td>Set functions</td></tr>
        <tr><td>Actors</td><td>Queues</td></tr>
        <tr><td>ORM</td><td>Declarative data manipulation</td></tr>
        <tr><td>Conditionals</td><td>Rules</td></tr>
        <tr><td>Inconsistency</td><td>Consistency</td></tr>
    </tbody>
    <thead>
        <tr><th>Construct</th><th>Complects</th></tr>
    </thead>
    <tbody>
        <tr><td>State</td><td>Everything that touches it</td></tr>
        <tr><td>Objects</td><td>State, identity, value</td></tr>
        <tr><td>Methods</td><td>Function and state, namespaces</td></tr>
        <tr><td>Syntax</td><td>Meaning, order</td></tr>
        <tr><td>Inheritance</td><td>Types</td></tr>
        <tr><td>Switch/matching</td><td>Multiple who/what pairs</td></tr>
        <tr><td>var(iable)s</td><td>Value, time</td></tr>
        <tr><td>Imperative loops, fold</td><td>what/how</td></tr>
        <tr><td>Actors</td><td>what/who</td></tr>
        <tr><td>ORM</td><td>OMG</td></tr>
        <tr><td>Conditionals</td><td>Why, rest of program</td></tr>
    </tbody>
    <thead>
        <tr><th>Construct</th><th>Get it via...</th></tr>
    </thead>
    <tbody>
        <tr><td>Values</td><td>final, persistent collections</td></tr>
        <tr><td>Functions</td><td>a.k.a. stateless methodsd</td></tr>
        <tr><td>Namespaces</td><td>language support</td></tr>
        <tr><td>Data</td><td>Maps, arrays, sets, XML, JSON etc</td></tr>
        <tr><td>Polymorphism a la carte</td><td>Protocols, type classes</td></tr>
        <tr><td>Managed refs</td><td>Clojure/Haskell refs</td></tr>
        <tr><td>Set functions</td><td>Libraries</td></tr>
        <tr><td>Queues</td><td>Libraries</td></tr>
        <tr><td>Declarative data manipulation</td><td>SQL/LINQ/Datalog</td></tr>
        <tr><td>Rules</td><td>Libraries, Prolog</td></tr>
        <tr><td>Consistency</td><td>Transactions, values</td></tr>
    </tbody>
</table>

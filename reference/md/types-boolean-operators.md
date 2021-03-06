# Boolean operators

## Relational operators
Booleans respect relational operators:

<table class="table table-striped">
    <thead>
        <tr>
            <td>Operator</td>
            <td>Example</td>
            <td>Meaning</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><</td>
            <td>5 < 10</td>
            <td>"5 is less than 10"</td>
        </tr>
        <tr>
            <td>></td>
            <td>10 > 7</td>
            <td>"10 is greater than 7"</td>
        </tr>
        <tr>
            <td><=</td>
            <td>5 <= 10</td>
            <td>"5 is less than or equal to 10"</td>
        </tr>
        <tr>
            <td>>=</td>
            <td>10 >= 7</td>
            <td>"10 is greater than or equal to 7"</td>
        </tr>
        <tr>
            <td>==</td>
            <td>7 == 7</td>
            <td>"7 is equal to 7"</td>
        </tr>
        <tr>
            <td>!=</td>
            <td>8 != 10</td>
            <td>"8 is not equal to 10"</td>
        </tr>
    </tbody>
</table>

## Boolean operators
Boolean operators allow you to express statements that combine pieces together.In English, we use words like *AND*, *OR*, *IS* and *NOT* to do this:

<ul>
    <li>"It <em>is</em> raining today <em>and</em> you should carry an umbrella."</li>
    <li>"I am full <em>or</em> the refridgerator is empty."</li>
    <li>"Your house is <em>not</em> the same as my house, <em>and</em> mine is better."</li>
</ul>

Boolean operators replace those words with keywords the computer can understand:

<table class="table table-striped">
    <thead>
        <tr>
            <td>Operator</td>
            <td>Example</td>
            <td>Translation</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>&&</td>
            <td>rain == true && umbrella == true</td>
            <td>"It's raining today and you should carry an umbrella"</td>
        </tr>
        <tr>
            <td>||</td>
            <td>full == true || emptyRefridgerator == true</td>
            <td>"I am full or the refridgerator is empty."</td>
        </tr>
        <tr>
            <td>!</td>
            <td>yourHouse != myHouse && myHouse > yourHouse</td>
            <td>"Your house is not the same as my house, and mine is better."</td>
        </tr>
    </tbody>
</table>

Here's a few examples:

<table class="table table-striped">
    <thead>
        <tr>
            <td>Expression</td>
            <td>Translation</td>
            <td>Answer</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>!true</td>
            <td>"not true"</td>
            <td>false</td>
        </tr>
        <tr>
            <td>!!false</td>
            <td>"not not-false"</td>
            <td>true</td>
        </tr>
        <tr>
            <td>!(2 == 2)</td>
            <td>"2 isn't equal to 2"</td>
            <td>false</td>
        </tr>
        <tr>
            <td>7 > 4 && 8 > 34</td>
            <td>"7 is greater than four and 8 is greater than 34"</td>
            <td>false</td>
        </tr>
        <tr>
            <td>7 > 4 || 8 > 34</td>
            <td>"7 is greater than four or 8 is greater than 34"</td>
            <td>true</td>
        </tr>
    </tbody>
</table>
# \<question-3\>



## Question 1. Which of the following are interfaces of web applications?

a

## Question 2. Which of the following status codes denotes a server error?

e

## Question 3. Predict the output of the following code:
true education name surname residence age

## Question 4.
```
<link rel="import" href="../polymer/polymer-element.html">
<link rel="import" href="../iron-input/iron-input.html">

<dom-module id="question-3">
  <template>
    <style>
      :host {
        display: block;
      }
    </style>
    <h2>Hello [[name]]!</h2>
 
    <iron-input bind-value="{{bindValue}}">
      Name
      <input label="Name" value="{{name::input}}">
    </iron-input>
    <template is="dom-repeat" items="[[tasks]]" as="task">
      <ul>
        <li>[[task]]</li>
      </ul>
    </template>
  </template>

  <script>
    /**
     * `question-3`
     * 
     *
     * @customElement
     * @polymer
     * @demo demo/index.html
     */
    class Question3 extends Polymer.Element {
      static get is() { return 'question-3'; }
      static get properties() {
        return {
          name:{
            type: String,
            value: '',
            notify: true
          },
          tasks: {
            type: Array,
            value: ["task-1", "task-2", "task-3"]
          },
        };
      }
      
    }

    window.customElements.define(Question3.is, Question3);
  </script>
</dom-module>
```
## Question 8. Consider the following html code:

<style> .test{ display: inline; }
</style>

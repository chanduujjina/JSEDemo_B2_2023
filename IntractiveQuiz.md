# Java Identifiers - Interactive Quiz

## Question 1:
Which of the following is a valid Java identifier?

<button onclick="checkAnswer(this, false)">2ndVariable</button><br/>
<button onclick="checkAnswer(this, false)">my-variable</button><br/>
<button onclick="checkAnswer(this, true)">_myVariable</button><br/>
<button onclick="checkAnswer(this, false)">class</button><br/>

<p id="answer1" style="font-weight: bold;"></p>

<hr/>

## Question 2:
Can a Java identifier start with a dollar sign `$`?

<button onclick="checkAnswer(this, true)">Yes</button><br/>
<button onclick="checkAnswer(this, false)">No</button><br/>

<p id="answer2" style="font-weight: bold;"></p>

<hr/>

<script>
  function checkAnswer(button, isCorrect) {
    // Find the <p> tag directly after this question to show the answer
    const resultPara = button.parentElement.querySelector("p");
    if (!resultPara) return;

    if (isCorrect) {
      resultPara.innerText = "✅ Correct!";
      resultPara.style.color = "green";
    } else {
      resultPara.innerText = "❌ Incorrect!";
      resultPara.style.color = "red";
    }
  }
</script>

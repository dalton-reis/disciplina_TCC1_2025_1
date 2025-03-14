num1 = 10
num2 = 20
sum = num1 + num2

print("The sum of " .. num1 .. " and " .. num2 .. " is **" .. sum .. "**.")

{% assign num1 = 10 %}
{% assign num2 = 20 %}
{% assign sum = num1 | plus: num2 %}

The sum of {{ num1 }} and {{ num2 }} is **{{ sum }}**.

<!-- Markdown itself doesn't support variables directly, but you can use JavaScript inside Markdown files if they're processed accordingly. -->

<script>
  let num1 = 10;
  let num2 = 20;
  let sum = num1 + num2;
  document.write(`The sum of ${num1} and ${num2} is **${sum}**.`);
</script>

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
  "http://www.w3.org/TR/html4/loose.dtd">
<html lang="ru">
<head>
  <title>задание4</title>
</head>
<body>
<script type="text/javascript">
  for(let i=1; i<100; i++) {
    if (i%3 === 0 && i%5 === 0) {
      console.log('FizzBuzz');
    }
    else if (i%3 === 0) {
      console.log('Fizz');
    }
    else if (i%5 === 0) {
      console.log('Buzz');
    } else {
      console.log(i);
    }
  }

</script>
</body>

</html>

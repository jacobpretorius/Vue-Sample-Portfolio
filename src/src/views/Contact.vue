<template>
  <div class="contact">
    <h1>Contact me</h1>
    <form action="mailto:test@test.com" method="post" enctype="text/plain">
      Name:
      <br />
      <input type="text" name="name" />
      <br />E-mail:
      <br />
      <input type="text" name="mail" />
      <br />Comment:
      <br />
      <input type="text" name="comment" size="50" />
      <br />
      <br />
      <input type="submit" value="Send" />
      <input type="reset" value="Reset" />
    </form>
  </div>
</template>
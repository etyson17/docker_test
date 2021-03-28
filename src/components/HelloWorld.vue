<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <p>
            For more information contact me at (989)798-2710 or etyson17@gmail.com<br>
            check out my
            <a href="https://docs.google.com/document/d/1GCZBs2xu4hi8aMOzpLkUO01M3MnLnmO6wqVGIJMPwgM/edit?usp=sharing" target="_blank" rel="noopener">resume</a>!
        </p>
        <h3>Here is my github</h3>
        <ul>
            <li><a href="https://github.com/etyson17" target="_blank" rel="noopener">cool code stuff</a></li>
        </ul>
        <h3>Some Favorites</h3>
        <ul>
            <li><a href="https://www.youtube.com/watch?v=gatGb2tvGLE" target="_blank" rel="noopener">Song</a></li>
            <li><a href="http://triplecrownrecords.com/artists/a-will-away" target="_blank" rel="noopener">band</a></li>
            <li><a href="http://www.tipsybearbistro.com/menu.html" target="_blank" rel="noopener">restaurant</a></li>
        </ul>
        <h3>Some songs I tabbed out</h3>
        <ul>
            <li><a href="https://tabs.ultimate-guitar.com/tab/a-will-away/home-chords-2286825" target="_blank" rel="noopener">Home by A Will Away</a></li>
            <li><a href="https://tabs.ultimate-guitar.com/tab/five-finger-death-punch/i-apologize-tabs-2018697" target="_blank" rel="noopener">I apologize by Five finger death punch</a></li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

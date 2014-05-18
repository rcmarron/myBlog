<div class="content" id="home">
  <div id="sidebar-button">
    <img src="/images/sidebar-button.png">
  </div>
  <div id="post-info">
    <div id="cover-photo-container">
      <img id="cover-photo" src="/images/<%- @cover %>">
    </div>
    <div id="info-container">
      <h1 id="title"><%- @title %></h1>
      <span id="date"><%- @date.toDateString() %></span>
    </div>
  </div>

  <div class="post">
    <%- @content %>
  </div>
  <div class="colophon">
    <p>
      <span id="social">Find me on <a href="https://twitter.com/Rick_Marron">Twitter</a></span>
    </p>
  </div>
</div>

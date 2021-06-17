<template>
  <section class="maincontent">
    <div class="sidebar">
      <ul v-scroll-spy-active v-scroll-spy-link>
        <li>
          <a>Position I</a>
        </li>
        <li>
          <a>Postiion II</a>
        </li>
        <li>
          <a>Position III</a>
        </li>
      </ul>
    </div>

    <div class="content" v-scroll-spy>
      <div>
        <h2 id="position-i">
          Position I
          <a href="#position-i">#</a>
        </h2>
        <ul>
          <li>
            Does this thing
          </li>
        </ul>
        <p>
          <em><strong>Experience</strong>: No previous experience required.</em>
        </p>
      </div>
      <div>
        <h2 id="position-ii">
          Position II
          <a class="direct-link" href="#position-ii">#</a>
        </h2>
        <ul>
          <li>
            Does this and that.
          </li>
        </ul>
        <p>
          <em
            ><strong>Experience</strong>: Typically requires a minimum of 2
            years of professional experience.</em
          >
        </p>
      </div>
      <div>
        <h2 id="position-iii">
          Position III
          <a class="direct-link" href="#position-iii">#</a>
        </h2>
        <ul>
          <li>
            Does this and that AND the other thing.
          </li>
        </ul>
        <p>
          <em
            ><strong>Experience</strong>: Typically requires a minimum of 5
            years of professional experience.</em
          >
        </p>
      </div>
    </div>
  </section>
</template>

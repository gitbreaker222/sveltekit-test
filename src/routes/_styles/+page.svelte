<header class="header-space">
  <h1>UI-Board</h1>
  &nbsp;
  <span>
    Search: <kbd>CTRL/CMD+F</kbd>;
    View code: <kbd>F12</kbd> / <kbd>CMD+SHIFT+C</kbd>
  </span>
</header>

<main class="main ui-board" role="main">
  <div class="header-space"></div>
  <!--
    <section id="template">
      <div class="content-layout">
        <a href="#template"><pre>template:</pre></a><hr>

        <dl>
          <dt>selector</dt>
          <dd>

          </dd>
        </dl>

      </div>
    </section>
    -->

  <h2>Atoms:</h2>
  <section id="space">
    <div class="content-layout">

      <a href="#space">
        <pre>space:</pre></a>
      <hr>

      <dl class="breakpoints">
        <dt>Breakpoints</dt>
        <dd>
          <table>
            <thead>
              <tr>
                <th>xs</th>
                <th>sm</th>
                <th>md</th>
                <th>lg</th>
                <th>xl</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="xs"></td>
                <td class="sm"></td>
                <td class="md"></td>
                <td class="lg"></td>
                <td class="xl"></td>
              </tr>
            </tbody>
          </table>
        </dd>
      </dl>

      <dl>
        <dt>.header-space</dt>
        <dd>
          <div class="header-space demo-bg"></div>
        </dd>
      </dl>

      <dl>
        <dt>.content-layout</dt>
        <dd>
          <div class="content-layout-demo" style="width: 800px;">
            <div class="content-layout demo-bg">
              <span style="font-size: 3rem">
                800 x 100 (max width)
              </span>
            </div>
          </div>
          <div class="content-layout-demo" style="width: 1000px;">
            <div class="content-layout demo-bg">
              <span style="font-size: 3rem">
                1000 x 100
              </span>
            </div>
          </div>
        </dd>
      </dl>

    </div>
  </section>

  <section id="typography">
    <div class="content-layout">

      <a href="#typography">
        <pre>typography:</pre></a>
      <hr>

      <h1>Heading 1</h1>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <h4>Heading 4</h4>
      <p>
        paragraph Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ad quae a voluptate molestiae suscipit velit facere vitae ut, magnam eius fuga cum voluptates minus illum quos, recusandae magni eos.
      </p>

      <dl>
        <dt>text.h1</dt>
        <dd>
          <span class="h1">
            text
          </span>
        </dd>
      </dl>

    </div>
  </section>

  <section id="palette">
    <div class="content-layout">
      <a href="#palette">
        <pre>palette:</pre></a>
      <hr>

      <dl>
        <dt>@primary</dt>
        <dd class="primary"></dd>
        <dt>@secondary</dt>
        <dd class="secondary"></dd>
      </dl>

    </div>
  </section>

  <section id="input">
    <div class="content-layout">
      <a href="#input">
        <pre>input / form:</pre></a>
      <hr>

      <dl>
        <dt>button</dt>
        <dd>
          <button>button</button>
        </dd>
        <dt>button.button-outline</dt>
        <dd>
          <button class="button-outline">button</button>
        </dd>
        <dt>button.button-clear</dt>
        <dd class="demo-bg">
          <button class="btn button-clear">button</button>
        </dd>
      </dl>

      <dl>
        <dt>input[type=text]</dt>
        <dd>
          <label>Wish:
            <input type="text" placeholder="anything you like">
          </label>
        </dd>
        <dt>input[type=number]</dt>
        <dd>
          <label>
            How many puppies?
            <input type="number" value="100">
          </label>
        </dd>
        <dt>label.btn ~ input[type=file]</dt>
        <dd>
          <label for="fileUpload" class="btn">Upload File</label>
          <input type="file" id="fileUpload" class="show-for-sr">
        </dd>
        <dt>input:invalid</dt>
        <dd>
          <input type="number" value="0" min="1">
        </dd>
      </dl>

      <dl>
        <dt>textarea</dt>
        <dd>
          <label>
            What books did you read over summer break?
            <textarea placeholder="None"></textarea>
          </label>
        </dd>
      </dl>

      <dl>
        <dt>(fieldset legend) checkbox, radio</dt>
        <dd>
          <fieldset>
            <legend>Choose Your Favorite</legend>
            <input type="radio" name="pokemon" value="Red" id="pokemonRed" required><label for="pokemonRed">Red</label>
            <input type="radio" name="pokemon" value="Blue" id="pokemonBlue"><label for="pokemonBlue">Blue</label>
            <input type="radio" name="pokemon" value="Yellow" id="pokemonYellow"><label for="pokemonYellow">Yellow</label>
          </fieldset>
          <fieldset>
            <legend>Check these out</legend>
            <input id="checkbox1" type="checkbox"><label for="checkbox1">Checkbox 1</label>
            <input id="checkbox2" type="checkbox"><label for="checkbox2">Checkbox 2</label>
            <input id="checkbox3" type="checkbox"><label for="checkbox3">Checkbox 3</label>
          </fieldset>
        </dd>
      </dl>

      <dl>
        <dt>datalist</dt>
        <dd>
          <label for="ice-cream-choice">Choose a flavor:</label>
          <input list="ice-cream-flavors" id="ice-cream-choice" name="ice-cream-choice" />
          <datalist id="ice-cream-flavors">
            <option value="Chocolate">
            <option value="Mint">
            <option value="Strawberry">
            <option value="Vanilla">
          </datalist>
        </dd>

        <dt>select</dt>
        <dd>
          <label>Choose a flavor:
            <select>
              <option value="Chocolate">Chocolate</option>
              <option value="Mint">Mint</option>
              <option value="Strawberry">Strawberry</option>
              <option value="Vanilla">Vanilla</option>
            </select>
          </label>
        </dd>
        <dt>select[multiple]</dt>
        <dd>
          <label>Choose a flavor:
            <select multiple>
              <option value="Chocolate">Chocolate</option>
              <option value="Mint">Mint</option>
              <option value="Strawberry">Strawberry</option>
              <option value="Vanilla">Vanilla</option>
            </select>
          </label>
        </dd>
      </dl>

      <dl>
        <dt>meter</dt>
        <dd>
          <label for="battery">Battery:</label>

          <meter id="battery" min="0" max="100" low="33" high="66" optimum="80" value="32">
            at 50/100
          </meter>
          <meter id="battery" min="0" max="100" low="33" high="66" optimum="80" value="50">
            at 50/100
          </meter>
          <meter id="battery" min="0" max="100" low="33" high="66" optimum="80" value="66">
            at 50/100
          </meter>
        </dd>
      </dl>

      <dl>
        <dt>progress:indeterminate</dt>
        <dd>
          <label for="progress0">Hacking system:</label>
          <progress id="progress0" max="100" indeterminate>
          </progress>
        </dd>
        <dt>progress[value=0]</dt>
        <dd>
          <label for="progress1">Hacking system:</label>
          <progress id="progress1" max="100" value="0">
            0%
          </progress>
        </dd>
        <dt>progress[value=50]</dt>
        <dd>
          <label for="progress2">Hacking system:</label>
          <progress id="progress2" max="100" value="50">
            50%
          </progress>
        </dd>
        <dt>progress[value=100]</dt>
        <dd>
          <label for="progress3">Hacking system:</label>
          <progress id="progress3" max="100" value="100">
            100%
          </progress>
        </dd>
      </dl>

    </div>
  </section>

  <section id="table">
    <div class="content-layout">
      <a href="#table">
        <pre>table:</pre></a>
      <hr>

      <dl>
        <dt>table</dt>
        <dd>
          <table>
            <thead>
              <tr>
                <th colspan="2">The table header</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>The table body</td>
                <td>with two columns</td>
              </tr>
            </tbody>
          </table>
        </dd>
      </dl>

    </div>
  </section>

  <section id="inline-semantics">
    <div class="content-layout">
      <a href="#inline-semantics">
        <pre>inline-semantics:</pre></a>
      <hr>

      <dl>
        <dt>a</dt>
        <dd>
          <a>anchor</a>
        </dd>
      </dl>

      <dl>
        <dt>abbr</dt>
        <dd>
          In short: <abbr title="abbreviation">abbr</abbr>
        </dd>
      </dl>

      <dl>
        <dt>b</dt>
        <dd>
          <b>bold</b>
        </dd>
      </dl>

      <dl>
        <dt>em</dt>
        <dd>
          <em>emphasize</em>
        </dd>
      </dl>

      <dl>
        <dt>strong</dt>
        <dd>
          <strong>strong</strong>
        </dd>
      </dl>

      <dl>
        <dt>kbd</dt>
        <dd>
          <kbd>Ctrl</kbd>
        </dd>
      </dl>

      <dl>
        <dt>ruby, rb, rp, rt</dt>
        <dd>
          <ruby>
            <rb>漢</rb>
            <rb>字</rb>
            <rp>(</rp>
            <rt>kan
            <rt>ji
            <rp>)</rp>
          </ruby>
        </dd>
      </dl>

      <dl>
        <dt>s</dt>
        <dd>
          <s>strikethrough</s>
        </dd>
      </dl>

      <dl>
        <dt>sub</dt>
        <dd>
          Subscript O<sub>2</sub>
        </dd>
      </dl>

      <dl>
        <dt>sup</dt>
        <dd>
          Superscript m<sup>2</sup>
        </dd>
      </dl>

      <dl>
        <dt>time</dt>
        <dd>
          <time datetime="PT2H30M">2h 30m</time>
        </dd>
      </dl>

      <dl>
        <dt>u</dt>
        <dd>
          spelling <u>speling</u>
        </dd>
      </dl>

    </div>
  </section>

  <section id="grouping">
    <div class="content-layout">
      <a href="#grouping">
        <pre>grouping:</pre></a>
      <hr>

      <dl>
        <dt>p</dt>
        <dd>
          <p>paragraph</p>
        </dd>
      </dl>

      <dl>
        <dt>hr</dt>
        <dd>
          <hr />
        </dd>
      </dl>

      <dl>
        <dt>pre</dt>
        <dd>preformatted</dd>
      </dl>

      <dl>
        <dt>blockquote cite</dt>
        <dd>
          <blockquote>
            Never give up! Trust your instincts!
            <cite>Peppy</cite>
          </blockquote>
        </dd>
      </dl>

      <dl>
        <dt>ul li</dt>
        <dd>
          <ul>
            <li>unordered list item</li>
            <ul>
              <li>item lv 2</li>
            </ul>
            <li>list item</li>
            <li>list item</li>
          </ul>
        </dd>
      </dl>

      <dl>
        <dt>ol li</dt>
        <dd>
          <ol>
            <li>ordered list item</li>
            <ol>
              <li>item lvl 2</li>
            </ol>
            <li>list item</li>
            <li>list item</li>
          </ol>
        </dd>
      </dl>

      <dl>
        <dt>dl dt / dd</dt>
        <dd>
          <dl>
            <dt>definition term</dt>
            <dd>definition description</dd>
          </dl>
        </dd>
      </dl>

      <dl>
        <dt>figure / figcaption</dt>
        <dd>
          <figure>
            <img src="https://images.unsplash.com/photo-1587023705107-290e07a2355a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=80" alt="brown and black speaker on brown wooden shelf">
            <figcaption>By Susan Yin @syinq</figcaption>
          </figure>
        </dd>
      </dl>

    </div>
  </section>

  <h2>Molecules</h2>
  ...

</main>
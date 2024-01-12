<script setup lang="ts">
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
  <div id="app">
    <Header />
    <div class="body-content">
      <main id="main-doc">
        <section
          id="introduction"
          class=""
        >
          <header title="Unqualified CSGO Stratbook Introduction">
            Introduction <a
              href="#introduction"
              class="anchor-link"
            />
          </header>
          <article>
            <p>
              The Unqualified CSGO Stratbook was written to simplify communication between teams and the players in them. It's not always easy to be able to attend each and every practice a team might have, so this helps the coaches and IGLs to allocate stuff the players should focus on more. It should also help newer teams or struggling up-and-coming IGLs to sort out their strats and utility and send the files over to the rest of the team.
            </p>
            <p>
              The documentation will hopefully cover each and every section of the Unqualified CSGO Stratbook to make it easier for newer people to use. If you feel there's any need for clarification on a section or that a section is missing, then feel free to <a
                href="https://twitter.com/D3ATHKeeper"
                target="_blank"
              >@ me on twitter</a> and I'll see what I can do to help.
            </p>
          </article>
        </section>
        <section
          id="initial-setup"
          class=""
        >
          <header title="How to setup the Unqualified CSGO Stratbook">
            Setup <a
              href="#initial-setup"
              class="anchor-link"
            />
          </header>
          <article>
            <p>
              <strong>If you want strats</strong>:<br>
              To get the strats you just need to copy it to your documents folder. So the location would be "Documents\CSGO-Stratbook" on mobile and on desktop.<br>
              <br>
              <strong>If you don't want strats</strong>:<br>
              Just open the app normally and start creating your own maps, strats and whatever you can think of.
            </p>
          </article>
        </section>
        <section
          id="strat-type"
          class=""
        >
          <header title="What are the strat types in the Unqualified CSGO Stratbook">
            Strat Types <a
              href="#strat-type"
              class="anchor-link"
            />
          </header>
          <article>
            <ul>
              <li>
                Strat
                <p>
                  The first option, Strat, creates a new page where you can create your own strats with chapters for each of your strats. The majority of the strat should ideally be written in the 'Strat description' section and then you can go to each specific player, select their util and give them a really short summary with tagging what util they might want. You can even tag the util if it's in the utility section by using <a href="#custom-utility-tag">this markup</a>.
                </p>
              </li>
              <li>
                Util
                <p>
                  The second option, Util, creates a new page where you can add all of your utility lineups. You can alternatively, also use it to upload strat images and use it with your Strat document above. You can link YouTube videos with normal <a href="#markdown">markdown</a> and you can link to other utility parts of the same set by using <a href="#custom-utility-tag">this markup</a>.
                </p>
              </li>
              <li>
                Doc
                <p>
                  The third option, Doc, creates a new page where you can basically do anything you want. It's almost the same as the Strat page, but just without all the players. Here you can add extra stuff like explaining optimal settings, binds, links to videos or anything else you can think of. This also works with the basic <a href="#markdown">markdown</a> format.
                </p>
              </li>
            </ul>
          </article>
        </section>
        <section
          id="settings"
          class=""
        >
          <header title="What does the settings do in the Unqualified CSGO Stratbook">
            Settings <a
              href="#settings"
              class="anchor-link"
            />
          </header>
          <article>
            <ul>
              <li id="app-name">
                App Name <a
                  href="#app-name"
                  class="anchor-link"
                />
                <p>
                  This is the name you'll see in the title bar of the Application. This, however, won't work on mobile as far as I'm aware.
                </p>
              </li>
              <li id="edit-mode">
                Edit Mode <a
                  href="#edit-mode"
                  class="anchor-link"
                />
                <p>
                  This will toggle the app in and out of edit mode. When in edit mode, you'll see a ton of new buttons and options to actually edit everything and to add your own options.
                </p>
              </li>
              <li id="high-res-images">
                High Res Images <a
                  href="#high-res-images"
                  class="anchor-link"
                />
                <p>
                  This will allow images to be rendered fully without compression. The downside to this is that it'll also use more RAM, which might be an issue on lower end devices.
                </p>
              </li>
              <li id="theme">
                Theme <a
                  href="#theme"
                  class="anchor-link"
                />
                <p>
                  Everything should hopefully be self-explanatory here, but here you can change the font sizes in the app and also change the colours to fit your theme. Colours will either use simple colour names or you can just use the HEX colour codes for them.
                </p>
              </li>
              <li id="player-colours">
                Player Colours <a
                  href="#player-colours"
                  class="anchor-link"
                />
                <p>
                  These are the colours you'll see when in the strat view. Each player should have their own coloured box. In the future this will be covered by player pictures.
                </p>
              </li>
              <li id="tags">
                Tags <a
                  href="#tags"
                  class="anchor-link"
                />
                <p>
                  Tags are only used in the Utility view to allow users to mark what their strats do. In the future there will hopefully be a way to sort and filter through utility.
                </p>
              </li>
            </ul>
          </article>
        </section>
        <section id="markdown">
          <header title="Markdown for the Unqualified CSGO Stratbook">
            Markdown <a
              href="#markdown"
              class="anchor-link"
            />
          </header>
          <article>
            Markdown is a popular language used to format text. This was the easiest and cleanest way to have it in the program and a lot of it gets used on other platforms too.
            <ul>
              <li id="custom-utility-tag">
                Custom Utility Tag <a
                  href="#custom-utility-tag"
                  class="anchor-link"
                />
                <p>
                  This is custom markdown code I added for the program. To use it you'll need the folder name and then the utility name to link it properly.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          [CT Smoke](~1/1~)
                        </td>
                        <td>
                          <img
                            src="/logo.png"
                            alt="Unqualified CSGO Stratbook logo"
                          >
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="header">
                Header <a
                  href="#header"
                  class="anchor-link"
                />
                <p>
                  To create a heading you just need to add a `#` infront of your line and it'll correspond to the heading level you want.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          # Header
                        </td>
                        <td>
                          <h1>Header</h1>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ## Header
                        </td>
                        <td>
                          <h2>Header</h2>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ### Header
                        </td>
                        <td>
                          <h3>Header</h3>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          #### Header
                        </td>
                        <td>
                          <h4>Header</h4>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ##### Header
                        </td>
                        <td>
                          <h5>Header</h5>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ###### Header
                        </td>
                        <td>
                          <h6>Header</h6>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="paragraphs">
                Paragraphs <a
                  href="#paragraphs"
                  class="anchor-link"
                />
                <p>
                  Just use a blank space in the next line.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          One line.
                          <br>
                          Second line.
                        </td>
                        <td>
                          One line.
                          <br>
                          Second line.
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="line-breaks">
                Line Breaks <a
                  href="#line-breaks"
                  class="anchor-link"
                />
                <p>
                  End a line with two or more space and then press return. You can also use `\` for multiple line breaks. I have also discovered certain situations, specifically with QML / Qt markdown where they don't work. The third method should work if the first two don't work for you.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          One line.  <br>
                          Second line.
                        </td>
                        <td>
                          One line.<br>
                          Second line.
                        </td>
                      </tr>
                      <tr>
                        <td>
                          Hello<br>
                          \<br>
                          \<br>
                          \<br>
                          World!
                        </td>
                        <td>
                          Hello
                          <br>
                          <br>
                          <br>
                          World!
                        </td>
                      </tr>
                      <tr>
                        <td>
                          Weird<br>
                          &lt;br/&gt;\<br>
                          &lt;br/&gt;<br>
                          Solution
                        </td>
                        <td>
                          Weird<br>
                          <br>
                          Solution
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="strikethrough">
                Strikethrough <a
                  href="#strikethrough"
                  class="anchor-link"
                />
                <p>
                  Just writing text between two tildes should make it striked out.
                </p>
                <p>
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          ~Oops, forget.~
                        </td>
                        <td>
                          <strike>Oops, forget.</strike>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="bold">
                Bold <a
                  href="#bold"
                  class="anchor-link"
                />
                <p>
                  You need to write your word or phrase between two astrisks or underscores to make it bold.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          **astrisks**
                        </td>
                        <td>
                          <strong>astrisks</strong>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          __underscores__
                        </td>
                        <td>
                          <strong>underscores</strong>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="italic">
                Italic <a
                  href="#italic"
                  class="anchor-link"
                />
                <p>
                  To create Italic text you need to write your text or phrases between astrisks or underscores.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          *astrisks*
                        </td>
                        <td>
                          <em>astrisks</em>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          _underscores_
                        </td>
                        <td>
                          <em>underscores</em>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="bold-and-italic">
                Bold and Italic <a
                  href="#bold-and-italic"
                  class="anchor-link"
                />
                <p>
                  You just have to combine the two. So write your words or phrases between three astrisks or underscores.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          ***Bold + Italic***
                        </td>
                        <td>
                          <strong><em>Bold + Italic</em></strong>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ___Bold + Italic___
                        </td>
                        <td>
                          <strong><em>Bold + Italic</em></strong>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          **_Bold + Italic_**
                        </td>
                        <td>
                          <strong><em>Bold + Italic</em></strong>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          __*Bold + Italic*__
                        </td>
                        <td>
                          <em><strong>Bold + Italic</strong></em>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="blockquotes">
                Blockquotes <a
                  href="#blockquotes"
                  class="anchor-link"
                />
                <p>
                  Add a `>` infront of each paragraph to create a blockqoute.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          > If we win more rounds than we lose, we will win the game <br>
                          >  n0thing
                        </td>
                        <td>
                          <blockquote>
                            If we win more rounds than we lose, we will win the game <br>
                            n0thing
                          </blockquote>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="unordered-lists">
                Unordered Lists <a
                  href="#unordered-lists"
                  class="anchor-link"
                />
                <p>
                  Add a `-`, `*` or `+` infront of any item to create an unordered list.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          - Item<br>
                          - Item<br>
                          - Item<br>
                        </td>
                        <td>
                          <ul>
                            <li>Item</li>
                            <li>Item</li>
                            <li>Item</li>
                          </ul>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          * Item<br>
                          * Item<br>
                          * Item<br>
                        </td>
                        <td>
                          <ul>
                            <li>Item</li>
                            <li>Item</li>
                            <li>Item</li>
                          </ul>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          + Item<br>
                          + Item<br>
                          + Item<br>
                        </td>
                        <td>
                          <ul>
                            <li>Item</li>
                            <li>Item</li>
                            <li>Item</li>
                          </ul>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="images">
                Images <a
                  href="#images"
                  class="anchor-link"
                />
                <p>
                  You can add any images inline into docs or strats, but the issue with this is that it won't have proper scaling. The image will just oveflow on smaller devices if the resolution is too big.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          ![CSGO Stratbook](logo.png)
                        </td>
                        <td>
                          <img
                            src="/logo.png"
                            alt="Unqualified CSGO Stratbook logo"
                          >
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="code">
                Code <a
                  href="#code"
                  class="anchor-link"
                />
                <p>
                  Allows you to display code or just have text displayed in a different format.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          `Your Code`
                        </td>
                        <td>
                          <code>
                            Your Code
                          </code>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="code-blocks">
                Code Blocks <a
                  href="#code-blocks"
                  class="anchor-link"
                />
                <p>
                  Allows you to display code or just have text displayed in a different format.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          ```<br>
                          Your Code<br>
                          ````<br>
                        </td>
                        <td>
                          <code>
                            Your Code
                          </code>
                        </td>
                      </tr>
                      <tr>
                        <td>
                          ~~~<br>
                          Your Code<br>
                          ~~~<br>
                        </td>
                        <td>
                          <code>
                            Your Code
                          </code>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="links">
                Links <a
                  href="#links"
                  class="anchor-link"
                />
                <p>
                  In the first set of brackets you need to write the title of your link and thenk in the second you just paste the link.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          [CSGO Stratbook](https://unqualified-csgo.com/)
                        </td>
                        <td>
                          <a href="https://unqualified-csgo.com/">CSGO Stratbook</a>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="tables">
                Tables <a
                  href="#tables"
                  class="anchor-link"
                />
                <p>
                  To create a table you need to follow the markdown below. You can add more dashes if you want, but a minimum of 3 is needed. Keep in mind that the tables won't be styled as they are here.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          | Syntax | Description |<br>
                          | --- | --- |<br>
                          | Header | Title |<br>
                          | Paragraph | Text |<br>
                        </td>
                        <td>
                          <table>
                            <thead>
                              <tr>
                                <th>
                                  Syntax
                                </th>
                                <th>
                                  Description
                                </th>
                              </tr>
                            </thead>
                            <tbody>
                              <tr>
                                <td>Header</td>
                                <td>Title</td>
                              </tr>
                              <tr>
                                <td>Paragraph</td>
                                <td>Text</td>
                              </tr>
                            </tbody>
                          </table>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
              <li id="task-list">
                Task List <a
                  href="#task-list"
                  class="anchor-link"
                />
                <p>
                  Creates a task list, but it can only be updated in edit mode.
                  <table>
                    <thead>
                      <tr>
                        <th>Markdown</th>
                        <th>Output</th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <td>
                          - [x] Create a team<br>
                          - [ ] Create utility<br>
                          - [ ] Create strats<br>
                        </td>
                        <td>
                          <input
                            type="checkbox"
                            checked
                            disabled
                          >
                          <label> Create a team</label><br>
                          <input
                            type="checkbox"
                            disabled
                          >
                          <label> Create utility</label><br>
                          <input
                            type="checkbox"
                            disabled
                          >
                          <label> Create strats</label><br>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </p>
              </li>
            </ul>
          </article>
        </section>
        <section id="software-used">
          <header title="Unqualified CSGO Stratbook written in">
            Software Used <a
              href="#software-used"
              class="anchor-link"
            />
          </header>
          <article>
            The Unqualified CSGO Stratbook is written in Qt C++ and Qt Qml for the views. All the settings files are written in JSON.
          </article>
        </section>
      </main>
      <Footer />
    </div>
  </div>
</template>

<style lang="scss">
    header {
    color: #66FcF1;
    margin: 10px;
    text-align: center;
    font-size: 1.8em;
    font-weight: thin;
  }
  h1 {
    font-size: 2em;
  }
  #main-doc header {
    text-align: left;
    margin: 0px;
  }
  #main-doc {
    /* position: absolute; */
    padding: 5rem 2rem;
    /* margin-bottom: 110px; */
  }
  section article {
    color: #C5C6C7;
    margin: 15px;
    font-size: 0.96em;
  }
  section > li {
    margin: 15px 0px 0px 20px;
  }
  header:hover .anchor-link,
  li:hover .anchor-link {
    display: inline-block;
  }
  header .anchor-link {
    margin-top: 7px;
  }
  .anchor-link {
    display: none;
    position: absolute;
    width: 20px;
    height: 20px;
    margin-left: 0.25rem;
  }
  code {
    display: block;
    text-align: left;
    white-space: pre-line;
    position: relative;
    word-break: normal;
    word-wrap: normal;
    /* line-height: 2; */
    /* background-color: #f7f7f7; */
    /* padding: 15px; */
    /* margin: 10px; */
    /* border-radius: 5px; */
  }
  a {
    color: #66FcF1;
  }
  table {
    border-collapse: collapse;
    border-radius: 6px;
    box-shadow: 0 0px 6px rgb(0, 0, 0);
    min-width: 250px;
  }
  thead tr th {
    background-color: #1F2833;
    padding: 0.5rem 0;
    text-align: center;
  }
  th:first-child {
    border-radius: 6px 0 0 0;
  }

  th:last-child {
    border-radius: 0 6px 0 0;
  }

  th:only-child{
    border-radius: 6px 6px 0 0;
  }
  tbody tr td {
    padding: 1rem 0.5rem;
    border-left: 1px solid #111;
    border-top: 1px solid #111;
  }

  table td:first-child, table th:first-child {
    border-left: none;
  }

  @media only screen and (max-width: 815px) {
    #main-doc {
      position: relative;
      margin-left: 0px;
      padding: 1rem;
      /* margin-top: 270px; */
    }
  }

  @media only screen and (max-width: 400px) {
    #main-doc {
      margin-left: -10px;
    }

    code {
      margin-left: -20px;
      width: 100%;
      padding: 15px;
      padding-left: 10px;
      padding-right: 45px;
      min-width: 233px;
    }
  }
</style>

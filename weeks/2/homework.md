# Due Before Next Class

**1. Create UI Prototypes**

* Pick at least one user story and create a corresponding HTML page for each.
* Don't pick the "Login" or "Create a User Account" type of story.
* Sync all of your HTML and CSS files into your Mockup repository.
* You should end up with at least one HTML/CSS mockup (`.html` file).

**2. Domain Modeling**

Update the `README.md` in your user_stories repository with a link to a Google Spreadsheet (or other online document, etc.) containing your domain model for your project.  You should have at least three tables.

  * Use **plural nouns** for table names: products, customers, songs, movies.
  * Make sure each table as a column named **id**.
  * Identify the name and type of each column.
  * Remember that each column can hold a single value only, not a list of values.

#### Column Types You Can Use

<table class="table table-bordered">
  <thead>
    <tr>
      <td colspan="3" style="background: #c5ffe0">Column Data Types</td>
    </tr>
    <tr>
      <th>Type</th>
      <th>Description</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
      <tr>
        <td>integer</td>
        <td>An integer</td>
        <td>Good for row identifiers, prices, and simple numbers</td>
      </tr>
      <tr>
        <td>string</td>
        <td>Short text up to 250 characters</td>
        <td>Good for a headline, title, or tweet</td>
      </tr>
      <tr>
        <td>text</td>
        <td>Long text, up to 2Gb</td>
        <td>An entire article or book</td>
      </tr>
      <tr>
        <td>boolean</td>
        <td><b>true</b> or <b>false</b></td>
        <td>Good for checkboxes, on/off states, yes/no answers, etc.</td>
      </tr>
      <tr>
        <td>datetime</td>
        <td>A date with a timestamp</td>
        <td></td>
      </tr>
      <tr>
        <td>date</td>
        <td>Just the date</td>
        <td></td>
      </tr>
      <tr>
        <td>float</td>
        <td>A number with decimal point</td>
        <td>If you need non-integer numerical values</td>
      </tr>
  </tbody>
</table>

#### Example

<table class="table table-bordered">
  <thead>
    <tr>
      <td colspan="5" style="background: #fffbce">Movies</td>
    </tr>
    <tr>
      <th>id<br>(integer)</th>
      <th>title<br>(string)</th>
      <th>year<br>(integer)</th>
      <th>synopsis<br>(text)</th>
      <th>director_id<br>(integer)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Raiders of the Lost Ark</td>
      <td>1983</td>
      <td>I hate rats.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Apollo 13</td>
      <td>1995</td>
      <td>Wonderful documentary about computers, people, and error messages.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Lincoln</td>
      <td>2012</td>
      <td>He dies at the end.  (Oops, should have said "spoiler alert")</td>
      <td>2</td>
    </tr>
  </tbody>
</table>

<table class="table table-bordered">
  <thead>
    <tr>
      <td colspan="5" style="background: #fffbce">Directors</td>
    </tr>
    <tr>
      <th>id<br>(integer)</th>
      <th>name<br>(string)</th>
      <th>dob<br>(date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Ron Howard</td>
      <td>July 1, 1949</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Steven Spielberg</td>
      <td>July 1, 1939</td>
    </tr>
  </tbody>
</table>

**3. Take the Self-Assessment**

Each week you'll need to update your personal assessment profile on my website.  It will require you to login with your GitHub account in order to access it.

* [My Assessment Profile](http://jeffcohenonline.com/assessment)

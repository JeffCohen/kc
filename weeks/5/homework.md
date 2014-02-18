# Due by Wednesday, Feb 12th, 1:00 PM

This is the last homework of the quarter!

## Preparation

1. Go to https://github.com/kiei925-winter14/week5-homework
1. Fork the repository into your own account.
1. Clone your new repository down to your laptop.
1. Open the code in Sublime Text.
1. Using your command prompt:
  1. Use the `cd` command to change to your app's directory
  1. Run the command: `bundle install`
  1. Run the command: `rails server`
  1. `http://localhost:3000/products/index` should result in an empty product catalog.

## Tasks
Replicate what we built in class.  We added a Product model with the following schema:

<table class="table table-bordered">
  <thead>
    <tr>
      <td colspan="4" style="background: #c5ffe0">Column Data Types</td>
    </tr>
    <tr>
      <th>id</th>
      <th>name</th>
      <th>image_url</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
      <tr>
        <td>integer</td>
        <td>string</td>
        <td>string</td>
        <td>text</td>
      </tr>
  </tbody>
</table>


1. Generate a `Product` model with the Model generator. Your Product model should have the schema above. HINT: See the [Cheat Sheet](/rails-models.pdf).
2. Check your new migration file and make sure it looks good.
3. Run your migration file with `rake db:migrate`.
4. Use the `rails console` to add a couple rows of product data.
1. "http://localhost:3000/products/index" should display your list of products.

## HINTS

Problems with your migration file?  Run `rake db:drop`.  Edit your migration file by hand to fix any problems.  Then try `rake db:migrate` again.

To add rows of data, use the `rails console`.  Here's an example:

```ruby
> rails console
irb(main):001:0> Product.count
0
irb(main):001:0> p = Product.new
irb(main):001:0> p.name = "iPhone"
irb(main):001:0> p.description = "Something witty goes here"
irb(main):001:0> p.image_url = "http://images.apple.com/iphone-5s/specs/images/color_gray.jpg"
irb(main):001:0> p.save
irb(main):001:0> Product.count
1
irb(main):001:0> exit
```



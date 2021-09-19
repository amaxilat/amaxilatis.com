[comment]: <> (---)

[comment]: <> (layout: page)

[comment]: <> (title: Contact)

[comment]: <> (permalink: /contact/)

[comment]: <> (description: I care about my readers' opinions. Please leave a note or just say hello.)

[comment]: <> (---)

[comment]: <> (### Write to me)

[comment]: <> (I care about my readers' opinions. Please leave a note or just say hello.)


[comment]: <> (<form action="https://formspree.io/{{site.data.main.email}}" method="POST">)

[comment]: <> (  <div class="form-group">)

[comment]: <> (    <label for="email">Email address</label>)

[comment]: <> (    <input type="email" name="email" class="form-control" placeholder="Enter email">)

[comment]: <> (  </div>)

[comment]: <> (  <div class="form-group">)

[comment]: <> (    <label for="message">Example textarea</label>)

[comment]: <> (    <textarea class="form-control" name="content" id="" rows="3" placeholder="Enter your message"></textarea>)

[comment]: <> (  </div>)

[comment]: <> (  <input type="hidden" name="_next" value="{{site.url}}{{page.url}}">)

[comment]: <> (  <input type="hidden" name="_subject" value="New Contact Form Submission">)

[comment]: <> (  <input type="text" name="_gotcha" style="display:none">)

[comment]: <> (  <button type="submit" class="btn btn-success">Submit</button>)

[comment]: <> (</form>)

[comment]: <> (<br>)

[comment]: <> (<br>)


[comment]: <> ({% highlight html %})

[comment]: <> (This form starts working once you update your email in configuration. Delete this line in the contact page found in the path _pages/contact.md)

[comment]: <> ({% endhighlight %})

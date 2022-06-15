Hi, I am a software developer and computer science undergraduate at the <a href="https://www.cs.ubc.ca/about-our-department" target="_blank" rel="noreferrer noopener">University of British Columbia</a>.

I am most comfortable with C++ and Elixir. I have also written bits of Java, Bash, C, SQL, JavaScript, and Python.

I value working in lean, agile teams with open-minded, pragmatic idealists. At this time, I am based in western Canada and open to remote work. 
My mailbox is open, please feel free to reach out at the address printed on [my site](https://peytonseigo.ca).

<br>

```elixir
%{
  my_site: {"peytonseigo.ca", "https://peytonseigo.ca"},
  linkedin: {"LinkedIn", "https://linkedin.com/in/peytonseigo"}
}
|> Enum.map(fn {_, {name, url}} -> "**[#{name}](#{url})**" end)
|> Enum.reduce(&(&1 <> ", " <> &2))
|> (&("˗ˏˋ˖⁺‧₊ #{&1} ₊‧⁺ˎ˖ˊ˗")).()
|> User.append_to_bio(User.get_user!("pseigo"))
```

˗ˏˋ˖⁺‧₊ **[peytonseigo.ca](https://peytonseigo.ca/)**, **[LinkedIn](https://linkedin.com/in/peytonseigo)** ₊‧⁺ˎ˖ˊ˗

<!-- \[ **[peytonseigo.ca](https://peytonseigo.ca/)**, **[LinkedIn](https://linkedin.com/in/peytonseigo)** \] -->

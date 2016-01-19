# Start Rust
This is my (opinionated) guide to beginning programming using Rust. I should point out that I am still new to Rust, so if you think that something should be added or dropped, feel free to open an issue!

If you are using this guide, it is expected that you have prior programming experience. I have seen many good resources for learning Rust, but I can't recall any good resources for learning programming _using_ Rust.

### Getting Started
The first step to getting started with Rust is to download the compiler. There are two main methods to do this. The first way is to follow the instructions in [The Rust Book](https://doc.rust-lang.org/book/), but I would like to recommend an alternative method. An excellent tool called [multirust](https://github.com/brson/multirust) has been created that allows you to easily work with multiple versions of the Rust compiler. Rust has three release channels for the compiler: stable, beta, and nightly. A large percentage of Rust developers seem to work with nightly (I saw a split of 55% stable, 45% nightly in one poll), so it will be helpful later on to have the capability to easily switch. Multirust also makes it easy to update the rust compiler when a new version is released, and this alone makes it worth using.

At this point you should have the Rust compiler installed. You should also have Cargo, Rust's build tool, installed. You can verify this with `rustc -V` and `cargo -V`. Before you get programming, there is one more tool that I recommend you install; [rustfmt](https://github.com/rust-lang-nursery/rustfmt). Rustfmt formats your code according to style guidelines. Follow the instructions at its repository to get it installed, and install the plugin for your editor of choice.

Finally, we can begin working with Rust. At this point you should read through the first 3 chapters of [The Rust Book](https://doc.rust-lang.org/book/). You can skip much of the second chapter, because we've already covered installing Rust. You should go through all of the third chapter, so that you can get a feel for working with Rust. After reading through chapter 3, go ahead and read more about [cargo](http://doc.crates.io/guide.html). Cargo is a very important tool in the world of Rust, so taking some time early on to learn more about it will be helpful later on. At this point you should skim through chapters 4 and 5 of _The Rust Book_. If you're anything like me, reading both chapters without writing any code would be disheartening, so you should just skim through bits that look interesting for now. The book isn't going anywhere, so you can always come back to sections when you want to use them!

You should now have Rust setup, and you should have some understanding of how Rust works. Now we're going to get our hands dirty and start writing some code! A good series aimed at new rustaceans that I've found useful is Jadpole's [ArcadeRS](https://jadpole.github.io/arcaders/arcaders-1-0/). This series goes over building a video game in Rust, but it has a strong focus on teaching parts of Rust.

### Additional Resources
You should now have a handle on programming with Rust. Now you should go and learn whatever interests you! Here is a quick list of resources that you might find interesting or useful.

*Note that I've linked to the nightly versions of the first three resources*
[The Rust Book](https://doc.rust-lang.org/nightly/book/)
[Rustonomicon](https://doc.rust-lang.org/nightly/nomicon/)
[Rust Style Guide](https://doc.rust-lang.org/nightly/style/a)
[Phil Opp's Writing an OS in Rust](http://os.phil-opp.com/)
[Raspberry Pi Bare Metal Programming With Rust](https://blog.thiago.me/raspberry-pi-bare-metal-programming-with-rust/)

Know of a good resource that I haven't listed here? Submit a pull request, or open an issue!

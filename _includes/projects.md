### [Turtle](https://turtle.rs/) - Create Animated Drawings Quickly and Easily in Rust
* **Repo**: https://github.com/sunjay/turtle
* **Contact**: https://turtle.zulipchat.com/
* **Spoken Languages**: English, _Canadian English_
* **Recommended Experience**: Beginner - Intermediate
* **Topics**: 2D Computer Graphics, Game Engine, Interprocess-Communication, Async, WebAssembly
* **Timezone**: PST (GMT-8)

### [Dotenv-linter](https://dotenv-linter.github.io) - ⚡️ Lightning-fast linter for `.env` files. Written in Rust 🦀
* **Repo**: https://github.com/dotenv-linter/dotenv-linter
* **Contact**: https://twitter.com/mgrachev
* **Spoken Languages**: English
* **Recommended Experience**: Beginner
* **Topics**: CLI, Linters, Dotenv
* **Timezone**: MSK (GMT+3)

### [OpenPowerlifting](https://www.openpowerlifting.org/) - Database, compiler, webserver, and data for the sport of Powerlifting. It's all Rust!
* **Repo**: [https://gitlab.com/openpowerlifting/opl-data](https://gitlab.com/openpowerlifting/opl-data)
* **Contact**: [https://openpl.zulipchat.com/](https://openpl.zulipchat.com/) (Say hi, or message Sean Stangl if you're shy!)
* **Spoken Languages**: English, Esperanto
* **Recommended Experience**: Beginner - Intermediate
* **Topics**: Webservers, Compilers, Databases, Data Analysis
* **Timezone**: MST (GMT-7)

### [cargo-tarpaulin](https://github.com/xd009642/tarpaulin) - Code coverage for rust, source analysis, tracing, reporting
* **Repo** [https://github.com/xd009642/tarpaulin](https://github.com/xd009642/tarpaulin)
* **Contact** Email ([danielmckenna93@gmail.com](mailto:danielmckenna93@gmail.com)) Discord (xd009642#3296)
* **Spoken Languages**: English
* **Recommended Experience**: All
* **Topics**: Code coverage, CLI tools, Interprocess Communication, Binary analysis
* **Timezone**: GMT

### [Linfa](https://github.com/rust-ml/linfa/) - A Rust machine learning framework
* **Repo**: [https://github.com/rust-ml/linfa](https://github.com/rust-ml/linfa)
* **Contact**: https://rust-ml.zulipchat.com/
* **Mentors**: https://github.com/quietlychris, https://github.com/bytesnake
* **Spoken Languages**: English, German
* **Recommended Experience**: Beginner - Intermediate
* **Topics**: Machine Learning, Data analysis, Clustering, Algorithms

<h1 id="projects-end"></h1>

<script>
var people = [];
var e = document.getElementById("project-mentorship");
while (e.nextSibling.nodeName != 'H3') e.nextSibling.remove();
e = e.nextSibling;
do {
    let person = [];
    do {
        person.push(e);
        e = e.nextSibling;
    } while (!/^H[123]$/i.test(e.nodeName));
    people.push(person);
} while (e.nodeName == 'H3');
for (let i = people.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [people[i], people[j]] = [people[j], people[i]];
}
people.forEach(person => {
    person.forEach(x => {
        e.parentNode.insertBefore(x, e);
    });
});
e.remove();
</script>

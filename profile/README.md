<h1><img alt="" height=34 valign=bottom src="https://i.imgur.com/IjWoNJM.png">&ensp;Typst Community</h1>

👨‍👩‍👧‍👦 Unofficial community hub for Typst community projects \
<sub>[⭐ Check out the official Typst project's GitHub page too!](https://github.com/typst)</sub>

### How do I get Typst?

<details><summary>⭐ Install Typst from GitHub release</summary>
<br>

1. Go to the [typst/typst latest release] page.
2. Pick the right bundle for your operating system and CPU architecture. Download it.
4. Extract the downloaded archive using `tar`, `unzip`, or your favorite extractor program.
5. Put your newly extracted `typst` binary somewhere on your `$PATH`.
  - On Linux that means someplace like `/usr/bin/typst` or `~/.local/bin/typst`.
  - On Windows that means create a new folder somewhere and [adding it to your `env:PATH`].

Now you can run `typst` in your terminal (PowerShell or `cmd`) to use Typst! 🎉

[typst/typst latest release]: https://github.com/typst/typst/releases/latest
[adding it to your `env:PATH`]: https://stackoverflow.com/a/44272417

</details>
<details><summary>⭐ Install Typst using Cargo</summary>
<br>

```sh
cargo install --git https://github.com/typst/typst typst-cli
```

[🚛 typst/typst Installation instructions](https://github.com/typst/typst#installation)

</details>
<details><summary>Install Typst using typst_install</summary>
<br>

```sh
curl -fsSL https://github.com/typst-community/typst_install/raw/main/install.sh | sh
```

[📚 typst-community/typst_install usage instructions](https://github.com/typst-community/typst_install#usage)

</details>
<details><summary>Install Typst using npm</summary>
<br>

```sh
npm install --global typst
# OR if you want to install it for the current project only
npm install --save-dev typst
# OR if you just want to run it once
npx typst
```

[📦 `typst` npm package](https://www.npmjs.com/package/typst)

</details>

[📚 Read more in the official typst/typst Installation section](https://github.com/typst/typst#installation)

## Whats new?

- **23.3.0** &mdash; Added the Rego language by [Alessio Fiorentino](https://github.com/fioreale) and changed the activation event for better startup speed.
- **23.2.0** &mdash; Added the Zig Language support.
- **23.1.0** &mdash; Hopefully the problem that happened in the installation is resolved. [#28](https://github.com/pouyakary/comment/issues/28)
- **23.0.0** &mdash; Added the optional setting for the new lines generated after a comment by [DL1NSA](https://github.com/DL1NSA)

- **22.0.0** &mdash; Renaming the Section comment to Title Comment and Line Comment to Separator Comment for better naming of these concepts. &mdash; Now supports international characters for titles like é or ز. &mdash; Supports PineScript :)

- **21.1.0** &mdash; Now moving the cursor to the end of title after renaming.

- **21.0.0** &mdash; New icon :)

- **20.3.0** &mdash; This version is mostly bug fixes. The comment detection system in editing the comment was broken and is now fully fixed. Also the comment editor now detects the ornament and preserves it so it will be only editing.

- **20.2.0** &mdash; An option in the settings (set to true on default) to only render ornaments in the root level.

- **20.1.0** &mdash; This version brings a much much better one line version of the comment for languages like C, HTML and CSS.

# Comment 6!

This version is a complete (yes complete!) rewrite of the whole extension. The extension is now written in a really clean TypeScript code base. Now is built on top of the Visual Studio Code **Web Extension API** and therefore works on web! And is way more customizable then before.

This means from this version you can edit your existing comments!

![Screen recording that shows the editing of a comment in Comment](https://user-images.githubusercontent.com/2157285/196059190-7adef113-05ad-4727-bbc2-dd84a860c146.gif)

The whole things is now much much more clean. After years of using and applying Comment V to my life and writing more than a 100 code bases with it, I've applied what I've learned to the new version. There are now only two comment types: Title Comment and Separator Comment. All the others were shiny objects that in time were obsolete and useless to the actual projects.

I'm going to bring more and more language features on the comments. Probably decorations for them and the code is now more clean and can be easily ported to other editors if someone is up for it.

Also the previous version [is available for download in the GitHub releases](https://github.com/pouyakary/comment/releases/tag/v11.2.0) if you miss it and want it back.

Really hope you like this one :)

---

- **11.0.2** &mdash; Support for SCSS added.
- **11.0.1** &mdash; Support for Terraform added.

- **11.0.0** &mdash; A big update:<br><br>Added native settings in the VS Code Settings<br><br>Added a fancy mode where you can have a signature or ornament at the end of your comments.<br><br>A new system of width computation where the comment is included and they are exactly 80 or 65 in width.<br><br>Added Fixed many problems in the previous version (I was lucked out of the vsce so sorry for the delay).

- **10.1.0** &mdash; Fixed the problem with Dockerfile, CPP, Arendelle, Processing, Java, C and ...

- **10.0.0** &mdash; From this version all comments are titled with all caps, and are not sensitive. This enables
  more codes to use Comment and probably easier integration.<br><br>If you wish to have the previous mode, you can have the `"comment": { "legacy": true }` within your `settings.json` <br><br>

- **7.1.1** &mdash; Peggy support added.
- **7.0.7** &mdash; Solidity support added.
- **7.0.6** &mdash; Dockerfile is now supported
- **7.0.5** &mdash; Rust Pest Language Added
- **7.0.6** &mdash; Rust changed to sensitive
- **7.0.5** &mdash; WebAssembly Text Format Added
- **7.0.3** &mdash; Languages V, Rust and Dart got added.
- **7.0.2** &mdash; Added the Ohm language
- **7.0.1** &mdash; nix language added by [@worldofspace](https://github.com/worldofpeace). (sorry for the late release...)
- **7.0.0** &mdash; This is a big release. The engine is now tailored to be more flexible and generate really better comments for Python and similar indentation-sensative languages.
- **6.1.0** &mdash; A problem with Separator comments regarding the spacings was fixed and also based on [a request](https://github.com/pmkary/comment-vscode/issues/5) six new characters are now accepted on the comment text: `-`, `+`, `:`, `@`, `?`, and `!`
- **6.0.0** &mdash; After a lot of requests... It now supports Multi separator comments! So languages like C, CSS, HTML, XML... are all now supported!
- **5.0.1** &mdash; GLSL Language Support Added.
- **5.0.0** &mdash; Reverse Title Comments are now supported.
- **4.0.6** &mdash; SQL language is now supported.
- **4.0.5** &mdash; Jison Language is now supported.
- **4.0.4** &mdash; yUML language is now supported.
- **4.0.3** &mdash; Nearley.js language is now supported.
- **4.0.2** &mdash; PEG.js language is now supported.
- **4.0.1** &mdash; Supporting Uno and Fish languages.
- **4.0.0** &mdash; Now having the awesome context menus.
- **3.0.10** &mdash; Separator comment improvements.
- **3.0.7** &mdash; YAML is now supported.

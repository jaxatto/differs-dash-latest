<h2>What</h2>
<p>This fork of @dvlden's <a href="https://github.com/dvlden/differs">differs</a> project provides a potential example of how to replace <code>@import</code> with <code>@use</code> and <code>@forward</code> <em>(aka the "module system")</em> per <a href="https://github.com/sass/dart-sass/releases/tag/1.23.0">Sass 1.23.0</a>.</p>

<p>Note, as of this writing, only <a href="https://github.com/sass/dart-sass">dart-sass</a> has this feature. lib-sass, and thusly node-sass, do not have an ETA publically posted when they will catch up.</p>

<h2>Why</h2>
<p>Sass plans to deprecate then drop support for @import <a href="https://github.com/sass/sass/blob/master/accepted/module-system.md#timeline">in the next 2 years</a></p>

<h2>How</h2>
<p><code>@import</code> is planned to be replaced with <code>@use</code> and <code>@forward</code>. You can <a href="https://sass-lang.com/documentation/at-rules/import">read more here</a> <a href="https://sass-lang.com/blog/the-module-system-is-launched">and here</a> on why</a>, but tldr; funky global nonsense, we want to define "imports" locally instead, so we know what's going on.</p>

<h2>Readings</h2>
<ul>
  <li><a href="https://sass-lang.com/documentation/at-rules/use">@use docs</a></li>
  <li><a href="https://sass-lang.com/documentation/at-rules/use">@forward docs</a></li>
  <li><a href="https://sass-lang.com/documentation/cli/migrator">@import Migration Tool</a></li>
  <li><a href="https://sass-lang.com/blog/the-module-system-is-launched">"The Module System is Launched"</a> <em>Natalie Weizenbaum</em</li>
  <li><a href="https://css-tricks.com/introducing-sass-modules/">"Introducing Sass Modules"</a> <em>Miriam Suzanne</em></li>
</ul>

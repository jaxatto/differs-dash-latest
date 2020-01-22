<h2>What</h2>
<p>This fork of @dvlden's <a href="https://github.com/dvlden/differs">differs</a> project provides a potential example of how to replace <code>@import</code> with <code>@use</code> and <code>@forward</code> per <a href="https://github.com/sass/dart-sass/releases/tag/1.23.0">Sass 1.23.0</a>.</p>

<p>Note, as of this writing, only <a href="https://github.com/sass/dart-sass">dart-sass</a> has this feature. lib-sass, and thusly node-sass, do not have an ETA publically posted when they will catch up.</p>

<h2>Why</h2>
<p>@dvlden's work is AWESOME, and I want to use it in another project of mine, but I can't use @import, as the current implementation is using. I thought I'd take a stab at a possible solution.</p>

<p>Sass plans to <a href="https://github.com/sass/sass/blob/master/accepted/module-system.md#timeline">drop support for @import</a> in 2022. It seems like a long way off, but I am trying to avoid starting new projects with soon-to-be deprecated features.</p>

<h2>How</h2>
<p><code>@import</code> is planned to be replaced with <code>@use</code> and <code>@forward</code>. You can <a href="https://sass-lang.com/documentation/at-rules/import">read more on why</a>, but tldr; funky global nonsense, we want to define "imports" locally instead, so we know what's going on.</p>


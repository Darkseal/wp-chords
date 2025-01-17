== WP Chords Fork ==
Contributors: Darkseal
Donate link: emreplt.com
Tags: chords, songs, guitar, ukulele, music, post, posts, lyrics, format, formatter, transpose, transposer, AMP, accelerated, mobile, pages, tablet, tabs
Requires at least: 4.6
Tested up to: 5.2.1
Stable tag: 1.0.0
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

WP Chords Fork allows you to to format and display the chords on your blog: it's a fork of WP Chords that fixes a bug in the semitone transpose feature to make it work.

== Description ==
***WP Chords Fork*** is a fork of Emre Polat's great [WP Chords](https://wordpress.org/plugins/wp-chords/) plugin, which allows you to format and display the chords on your blog. You can set font sizes, enable transposing chords especially in your posts. **Compatible with [Google AMP](http://amp.dev) (Accelerated Mobile Pages)**.  It's fully supported different devices such as tablets, mobile phones and most of web browsers.

This fork has been created to fix a bug in the original plugin that affects the semitone transpose feature, thus making it work. The list of features below is taken from the former plugin. For a complete explanation in the transpose feature fix and how it affects the former plugin's behaviour, [read this post](https://www.ryadel.com/en/wp-chords-plugin-worpdress-guitar/).

***WP Chords Fork*** is released under GPL v2 license, just like the former plugin: the full source code is also available on [GitHub](https://github.com/Darkseal/wp-chords).

### Eazy Real Time Demo

As soon as you install the WP Chords plugin, you will find live demo playground under **Settings**->**WP Chords**. You even don't need to create a post or a record in your database!

> Please follow **How can I test it?** directions in FAQ page.

### Formatting

You can define your chords at the correct positions in your song using chord shortcodes. 187 codes are available in below. On your final post view your chords will be automatically placed in their correct positions. You can configure formatting with some options such as below

= Formatting Features =
* Display with *monospace* font.
* Display with alternating chords.

### Transposing

On your final post view, visitors can adjust chord transposing as they wish with 17 half tones. On the transpose bar, the first chord in the song will be automatically selected as default tone.

= Transposing Features =
* Tones are: Ab, A, A#, Bb, B, C, C#, Db, D, D#, Db, E, F, F#, Gb, G, G#.
* Transposing can be turned off.

### Font Sizing

Your visitor can adjust font size for the song, while playing it.

= Font Sizing Features =
* It can be turned off

### Supported Chords:
Ab, Abm, Ab6, Ab7, Ab9, Abm6, Abm7, Abmaj7, Abdim, Ab+, Absus, A, Am, A6, A7, A9, Am6, Am7, Amaj7, Adim, A+, Asus, A#, A#m, A#6, A#7, A#9, A#m6, A#m7, A#maj7, A#dim, A#+, A#sus, Bb, Bbm, Bb6, Bb7, Bb9, Bbm6, Bbm7, Bbmaj7, Bbdim, Bb+, Bbsus, B, Bm, B6, B7, B9, Bm6, Bm7, Bmaj7, Bdim, B+, Bsus, C, Cm, C6, C7, C9, Cm6, Cm7, Cmaj7, Cdim, C+, Csus, C#, C#m, C#6, C#7, C#9, C#m6, C#m7, C#maj7, C#dim, C#+, C#sus, Db, Dbm, Db6, Db7, Db9, Dbm6, Dbm7, Dbmaj7, Dbdim, Db+, Dbsus, D, Dm, D6, D7, D9, Dm6, Dm7, Dmaj7, Ddim, D+, Dsus, D#, D#m, D#6, D#7, D#9, D#m6, D#m7, D#maj7, D#dim, D#+, D#sus, Eb, Ebm, Eb6, Eb7, Eb9, Ebm6, Ebm7, Ebmaj7, Ebdim, Eb+, Ebsus, E, Em, E6, E7, E9, Em6, Em7, Emaj7, Edim, E+, Esus, F, Fm, F6, F7, F9, Fm6, Fm7, Fmaj7, Fdim, F+, Fsus, F#, F#m, F#6, F#7, F#9, F#m6, F#m7, F#maj7, F#dim, F#+, F#sus, Gb, Gbm, Gb6, Gb7, Gb9, Gbm6, Gbm7, Gbmaj7, Gbdim, Gb+, Gbsus, G, Gm, G6, G7, G9, Gm6, Gm7, Gmaj7, Gdim, G+, Gsus, G#, G#m, G#6, G#7, G#9, G#m6, G#m7, G#maj7, G#dim, G#+, G#sus


== Installation ==

1. Upload the zipped file to your sites '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the Settings->WP Chords Fork screen to configure the plugin

== Frequently Asked Questions ==

= How can I use WP chords? =

After you installed/activated the plugin. You need to cover a content (like a song) with ‘[wpchords][/wpchords]’ shortcode.
Place chord codes inside your songs to correct positions.
Available chord codes are: [Ab], [Abm], [Ab6], [Ab7], [Ab9], [Abm6], [Abm7], [Abmaj7], [Abdim], [Ab+], [Absus], [A], [Am], [A6], [A7], [A9], [Am6], [Am7], [Amaj7], [Adim], [A+], [Asus], [A#], [A#m], [A#6], [A#7], [A#9], [A#m6], [A#m7], [A#maj7], [A#dim], [A#+], [A#sus], [Bb], [Bbm], [Bb6], [Bb7], [Bb9], [Bbm6], [Bbm7], [Bbmaj7], [Bbdim], [Bb+], [Bbsus], [B], [Bm], [B6], [B7], [B9], [Bm6], [Bm7], [Bmaj7], [Bdim], [B+], [Bsus], [C], [Cm], [C6], [C7], [C9], [Cm6], [Cm7], [Cmaj7], [Cdim], [C+], [Csus], [C#], [C#m], [C#6], [C#7], [C#9], [C#m6], [C#m7], [C#maj7], [C#dim], [C#+], [C#sus], [Db], [Dbm], [Db6], [Db7], [Db9], [Dbm6], [Dbm7], [Dbmaj7], [Dbdim], [Db+], [Dbsus], [D], [Dm], [D6], [D7], [D9], [Dm6], [Dm7], [Dmaj7], [Ddim], [D+], [Dsus], [D#], [D#m], [D#6], [D#7], [D#9], [D#m6], [D#m7], [D#maj7], [D#dim], [D#+], [D#sus], [Eb], [Ebm], [Eb6], [Eb7], [Eb9], [Ebm6], [Ebm7], [Ebmaj7], [Ebdim], [Eb+], [Ebsus], [E], [Em], [E6], [E7], [E9], [Em6], [Em7], [Emaj7], [Edim], [E+], [Esus], [F], [Fm], [F6], [F7], [F9], [Fm6], [Fm7], [Fmaj7], [Fdim], [F+], [Fsus], [F#], [F#m], [F#6], [F#7], [F#9], [F#m6], [F#m7], [F#maj7], [F#dim], [F#+], [F#sus], [Gb], [Gbm], [Gb6], [Gb7], [Gb9], [Gbm6], [Gbm7], [Gbmaj7], [Gbdim], [Gb+], [Gbsus], [G], [Gm], [G6], [G7], [G9], [Gm6], [Gm7], [Gmaj7], [Gdim], [G+], [Gsus], [G#], [G#m], [G#6], [G#7], [G#9], [G#m6], [G#m7], [G#maj7], [G#dim], [G#+], [G#sus].

= How can I test it? =

1. Go Settings->WP Chords Fork screen.
2. Find the "Settings with realtime demo" field.
3. Fill "Source" text area with the "How can I use WP chords?" directions.
4. In the "Result" section your song will be formatted with your configurations simultaneously.

= How can I show my chords with Google AMP? =

1. Install AMP plugin.
2. It will be automatically detected while you are in AMP view. Redirection link will be automatically placed over your song.

= How can I disable font sizing? =

1. Go Settings->WP Chords Fork screen to configure the plugin.
2. Check "Hide Font Size Changer".

= How can I disable chord transposing? =

1. Go Settings->WP Chords screen to configure the plugin.
2. Check "Hide Transpose".

= How can I show my chords with alternating display? =

1. Go Settings->WP Chords screen to configure the plugin.
2. Check "Display with Alternating Chords".

= How can I show my chords with monospace font? =

1. Go Settings->WP Chords screen to configure the plugin.
2. Check "Display with monospace font".

= How can I change AMP redirection text? =

1. Go Settings->WP Chords screen to configure the plugin.
2. Fill "Redirection to full page (If amp is enabled)" area with your desired text.

== Changelog ==

= 1.0.0 =
* Initial release (aligned to the 1.0.9 release of WP Chords).


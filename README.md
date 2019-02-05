#  Sevensi Roman Keyboards For macOS  #

This repository contains a macOS Keyboard Bundle, initially created
  with [Ukelele](https://scripts.sil.org/ukelele), and then edited by
  hand, for input of Romanized Sevensi text.
For more information on the design of the Sevensi Romanization, see
  <https://go.KIBI.family/Oct/2018/7c-text.xhtml>.

##  Installation  ##

01. Clone this repository, or download it as a ZIP and unzip its
      contents.

02. In Finder, click `Go > Go to Folder…` and type `~/Library`, then
      press Return to navigate to your user library folder.

03. Create the `Keyboard Layouts` directory if it doesn't already
      exist in this folder.

04. Drag `SevensiRoman.bundle` (from this repository) into the
      `Keyboard Layouts` folder.

##  Usage  ##

Open System Preferences, click on Keyboard, and then Input Sources.
Use the + button to add a new input source.
The "native" Sevensi Roman keyboard will be available under the `art`
  category (for artificial languages).
The Bilingual Sevensi Roman keyboard will be available under the
  English category.

##  Notes  ##

 +  The native keyboard does not use dead keys (instead outputting
      combining characters directly); typing is done in handwriting
      order.
    Consequently, the resulting output will be in a Unicode
      ‘decomposed’ form.

 +  The bilingual keyboard is the same as a typical US keyboard layout
      when the Option key is not held down.
    It has a large number of dead keys, most of which are located in
      the top row.

##  Changelog  ##

 +  **2.0 :**
    In Bilingual Sevensi Roman:

     +  Resturctured XML in files for better readability.

     +  OPTION + SPACE now produces NARROW NO-BREAK SPACE and SHIFT +
          OPTION + SPACE now produces NO-BREAK SPACE.

     +  The letters Ð, Ɂ, and Ʃ were added.

     +  Added the DOT ABOVE character and allowed it to combine with
          English consonants (and I).
        With small I and J, this gives the dotless variants.

     +  COMMA ABOVE RIGHT now has some special interactions: It
          combines with C to produce Ç, F to produce Ƒ, H to produce Ħ,
          small K to produce ᴋ, L to produce Ỻ, O to produce Ơ, small S
          to produce ſ, and Z to produce Ʒ.

     +  RING ABOVE now has some special interactions: It combines with
          D to produce Ꝺ, F to produce Ꝼ, G to produce Ᵹ, L to produce
          Ꝇ, O to produce Ꝍ, R to produce Ꞃ, T to produce Ꞇ, W to
          produce Ỽ, and Y to produce Ỿ.

     +  All consonants now can be combined with CARON, DOT ABOVE, and
          TILDE.

     +  HYPHEN was replaced with the sequence SOFT HYPHEN, NON-BREAKING
          HYPHEN; this ‘splits’ hyphens across linebreaks.

     +  Added TIRONIAN SIGN ET, DOUBLE HYPHEN, MIDDLE DOT, SWUNG DASH,
          HORIZONTAL BAR, and TWO-EM DASH.

     +  Removed a number of mathematical characters to make room for
          the above.

 +  **1.1 :**
    Fine-tuned by hand to fix some issues and decrease file sizes.

 +  **1.0 :**
    Initial release.

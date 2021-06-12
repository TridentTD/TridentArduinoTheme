**Sublime-like Theme for ArduinoIDE**
# Trident Arduino Theme

วิธีการติดตั้ง "ธีม"" นี้ ให้ ArduinoIDE
------

ให้เข้าไปที่ C:\Program Files (x86)\Arduino\lib

เปลี่ยนชื่อโฟลเดอร์ theme ในนั้น เป็น theme_backup

จากนั้นให้ สำเนา โฟลเดอร์ theme

ไปไว้ที่ C:\Program Files (x86)\Arduino\lib แทน

แล้วเปิด ArduinoIDE ขึ้นมาใหม่

ก็จะได้ธีม หน้าตาคล้าย Sublime Editor


![TridentArduinoTheme](TridentArduinoTheme.png)
   

#### Theme Settings  
Field ต่างๆ สำหรับ ปรับค่าเอง    
- Settings found in lib/theme/theme.txt:
  - `status.notice.fgcolor` - Non-error text color on the status bar.  - `buttons.bgcolor` - Color of the button bar.
  - `status.notice.bgcolor` - Background color of the status bar when not in error mode.
  - `status.error.fgcolor` - Text color of the Status Bar in error mode.
  - `status.error.bgcolor` - Background color of the Status Bar in error mode.
  - `status.edit.fgcolor` - Doesn't appear to have any effect.
  - `status.edit.bgcolor` - Doesn't appear to have any effect.
  - `status.font` - Status Bar text font.
  - `header.bgcolor` - Color behind the tabs.
  - `header.text.selected.color` - Color of the currently selected tab text.
  - `header.text.unselected.color` - Color of the unselected tab text.
  - `header.text.font` - Font of the Header text.
  - `console.font` - Font of console text.
  - `console.font.macosx` - Font of console text on Mac OS X.
  - `console.color` - Background color of the console.
  - `console.output.color` - Console text color for non-error/warning output.
  - `console.error.color` - Console text color for error/warning messages.
  - `buttons.bgcolor` - Button bar color.
  - `buttons.status.font` - Font of text shown to the right of the buttons when you hover over one.
  - `buttons.status.color` - Color of the text shown to the right of the buttons when you hover over one.
  - `plotting.bgcolor` - Background color of the Serial Plotter.
  - `plotting.color` - Doesn't appear to have any effect.
  - `plotting.gridcolor` - Color of the Serial Plotter grid.
  - `plotting.boundscolor` - Color of the bounds lines on the left and bottom margins of the Serial Plotter.
  - `plotting.graphcolor.size` - The number of Serial plotter line colors defined.
  - `plotting.graphcolor.nn` - Color of each line in Serial Plotter.
  - `linestatus.color` - Color of the text on the Line Status bar.
  - `linestatus.bgcolor` - Line Status bar background color.
  - `linestatus.font` - Font of the Line Status bar text.
  - `linestatus.height` - Height of the Line Status bar.
  - `editor.fgcolor` - Default editor text color.
  - `editor.bgcolor` - Background color of the editor window.
  - `editor.linehighlight.color` - Background color of the current line highlight (enabled by setting `editor.linehighlight=true`).
  - `editor.linehighlight` - Enable/disable highlighting of the line the cursor is on.
  - `editor.caret.color` - AKA cursor.
  - `editor.external.bgcolor` - Background color of the editor when **File > Preferences > Use external editor** is checked.
  - `editor.selection.color` - Background color of selected text.
  - `editor.invalid.style` - Doesn't appear to have any effect.
  - `editor.eolmarkers` - Enable/disable line end indicators(`¶`).
  - `editor.eolmarkers.color` - Color of line end indicators. (enabled by setting `editor.eolmarkers=true`).
  - `editor.brackethighlight` - Enable/disable highlighting of the bracket matching the one at the cursor position.
  - `editor.brackethighlight.color` - Matched bracket highlight foreground color. (enabled by setting `editor.brackethighlight=true`).
  - `editor.keyword1.style` - Doesn't appear to have any effect.
  - `editor.data_type.style` - `KEYWORD1` and `DATA_TYPE` keywords in the keywords.txt file of any installed library or {Arduino IDE installation folder}/lib/keywords.txt.
  - `editor.keyword2.style` - Doesn't appear to have any effect.
  - `editor.function.style` - `KEYWORD2`, `KEYWORD3`, and `LITERAL2` keywords in the keywords.txt file of any installed library or {Arduino IDE installation folder}/lib/keywords.txt.
  - `editor.keyword3.style` - Doesn't appear to have any effect.
  - `editor.reserved_word.style` - `RESERVED_WORD` keywords in the keywords.txt file of any installed library or {Arduino IDE installation folder}/lib/keywords.txt.
  - `editor.literal1.style` - Doesn't appear to have any effect.
  - `editor.literal2.style` - Doesn't appear to have any effect.
  - `editor.variable.style` - Doesn't appear to have any effect.
  - `editor.reserved_word_2.style` - `LITERAL1` and `RESERVED_WORD_2` keywords in the keywords.txt file of any installed library or {Arduino IDE installation folder}/lib/keywords.txt.
  - `editor.literal_boolean.style` - true or false
  - `editor.literal_char.style` - Doesn't appear to have any effect.
  - `editor.literal_string_double_quote.style` - Text surrounded by double quotes.
  - `editor.preprocessor.style` - Preprocessor directives(or `PREPROCESSOR` keywords in the keywords.txt file of any installed library).
  - `editor.url.style` - Doesn't appear to have any effect.
  - `editor.operator.style` - e.g. + - = /
  - `editor.label.style` - Doesn't appear to have any effect.
  - `editor.comment1.style` - C++ style comments.
  - `editor.comment2.style` - C style comments.

- Settings found in lib/theme/syntax/default.xml:
  - `<background color=` - Doesn't appear to have any effect.
  - `<caret color=` - Doesn't appear to have any effect.
  - `<selection`
    - `fg=` - Doesn't appear to have any effect.
    - `bg=` - Doesn't appear to have any effect.
  - `<currentLineHighlight`
    - `color=` - Doesn't appear to have any effect.
    - `fade=` - Doesn't appear to have any effect.
  - `<marginLine fg=` - Doesn't appear to have any effect.
  - `<markAllHighlight color=` - Doesn't appear to have any effect.
  - `<markOccurrencesHighlight`
    - `color=` - Doesn't appear to have any effect.
    - `border=` - Doesn't appear to have any effect.
  - `<matchedBracket` - Highlighting of the bracket matched to the one at the cursor position.
    - `fg=` - Doesn't appear to have any effect.
    - `bg=` - Matched bracket highlight background color.
    - `highlightBoth=` - Doesn't appear to have any effect.
    - `animate=` - Animation on matched bracket highlighting.
  - `<hyperlinks fg=` - Doesn't appear to have any effect.
  - `<secondaryLanguages>`
    - `<language`
      - `index=` - Doesn't appear to have any effect.
      - `bg=` - Doesn't appear to have any effect.
  - `<gutterBorder color=` - Doesn't appear to have any effect.
  - `<lineNumbers fg=` - Doesn't appear to have any effect.
  - `<foldIndicator`
    - `fg=` - Doesn't appear to have any effect.
    - `iconBg=` - Doesn't appear to have any effect.
  - `<iconRowHeader activeLineRange=` - Doesn't appear to have any effect.
  - `<style token="IDENTIFIER" fg=` - Doesn't appear to have any effect.
  - `<style token="DATA_TYPE"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="FUNCTION" fg=` - Doesn't appear to have any effect.
  - `<style token="VARIABLE"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="RESERVED_WORD"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="RESERVED_WORD_2"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="PREPROCESSOR"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="ANNOTATION" fg=` - Doesn't appear to have any effect.
  - `<style token="COMMENT_DOCUMENTATION" fg=` - Doesn't appear to have any effect.
  - `<style token="COMMENT_EOL" fg=` - Doesn't appear to have any effect.
  - `<style token="COMMENT_MULTILINE" fg=` - Doesn't appear to have any effect.
  - `<style token="COMMENT_KEYWORD" fg=` - Doesn't appear to have any effect.
  - `<style token="COMMENT_MARKUP" fg=` - Doesn't appear to have any effect.
  - `<style token="LITERAL_BOOLEAN"`
    - `fg=` - Doesn't appear to have any effect.
    - `bold=` - Doesn't appear to have any effect.
  - `<style token="LITERAL_NUMBER_FLOAT" fg=` - Doesn't appear to have any effect.
  - `<style token="LITERAL_NUMBER_DECIMAL_INT" fg=` - Integers.
  - `<style token="LITERAL_NUMBER_FLOAT" fg=` - Decimal fractions.
  - `<style token="LITERAL_NUMBER_HEXADECIMAL" fg=` - Numbers in hexadecimal form(start with 0x followed by only 0-9, A-F, a-f).
  - `<style token="LITERAL_STRING_DOUBLE_QUOTE" fg=` - Doesn't appear to have any effect.
  - `<style token="LITERAL_CHAR" fg=` - Doesn't appear to have any effect.
  - `<style token="LITERAL_BACKQUOTE" fg=` - Doesn't appear to have any effect.
  - `<style token="OPERATOR" fg=` - Doesn't appear to have any effect.
  - `<style token="REGEX" fg=` - Doesn't appear to have any effect.
  - `<style token="SEPARATOR" fg=` - Non-highlighted bracket.
  - `<style token="WHITESPACE" fg=` - Doesn't appear to have any effect.
  - `<style token="ERROR_IDENTIFIER" fg=` - Text that starts with a backtick.
  - `<style token="ERROR_NUMBER_FORMAT" fg=` - Doesn't appear to have any effect.
  - `<style token="ERROR_STRING_DOUBLE" fg=` - Text that starts with a double quote(but not text surrounded by double quotes).
  - `<style token="ERROR_CHAR" fg=` - Text that starts with a single quote(but not a single character surrounded by single quotes).
  

12 มิถุนายน พ.ศ.2560

วันจันทร์ แรม ๓ ค่ำ เดือน ๗ ปีระกา

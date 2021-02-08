#+TITLE: Vimgolf Challenges

Almost all(i.e. at the time of writing) the vimgolf challenges in one org file

This all the vim golf challenges that are scraped from [[vimgolf.com][vimgolf.com]].
I scraped and put them in a single org file because I am used to the format. I think
the challanges are good for any one working with any editor.

* table of contents                                                     :TOC_1:
- [[#box-it][Box it]]
- [[#simple-practical-and-common][Simple, Practical, and Common]]
- [[#ninja-substitution][ninja substitution]]
- [[#simple-format][simple format]]
- [[#one-number-per-line][One number per line]]
- [[#remove-lines-containing-the-word-reader][remove lines containing the word "reader"]]
- [[#one-to-ten][One to Ten]]
- [[#two-pairs-of-cluster-of-letters-creates-word][Two pairs of cluster of letters creates word]]
- [[#i-forgot-quotes][I forgot quotes]]
- [[#applying-same-text-modification-in-several-lines][Applying same text modification in several lines]]
- [[#cool-or-not][Cool or not?]]
- [[#leave-only-the-numbered-lines][Leave only the numbered lines.]]
- [[#comma-trouble][Com(m)a Trouble]]
- [[#words-in-parens][Words in parens]]
- [[#swap-values-inside-brackets][Swap values inside brackets]]
- [[#a-happy-new-year-2014-][A HAPPY NEW YEAR 2014 !]]
- [[#increment-each-number][Increment each number]]
- [[#vice-versa][Vice versa]]
- [[#resort-and-deup-a-csv-list][Resort and deup a CSV list]]
- [[#delete-to-the-end-of-the-current-line][Delete to the end of the current line]]
- [[#simple-text-editing-with-vim][Simple text editing with Vim]]
- [[#swap-values][Swap values]]
- [[#put-the-months-in-order][Put the months in order]]
- [[#change-part-of-a-function-name-in-multiple-occurrences][Change part of a function name in multiple occurrences]]
- [[#basic-renumbering][Basic renumbering]]
- [[#move-titles-next-to-url-in-quotes][move titles next to url, in quotes]]
- [[#team-names][Team names]]
- [[#collect-list][Collect List]]
- [[#convert-yml-into-java-pojo-field][convert yml into java pojo field]]
- [[#array-transposition][Array transposition]]
- [[#v-to-the-i][V to the i]]
- [[#convert-application-output-to-csv][Convert Application Output to CSV]]
- [[#every-other-line][Every other line]]
- [[#build-a-six][Build a six]]
- [[#copy-three-lines][Copy three lines]]
- [[#reformatrefactor-a-golfer-class][Reformat/Refactor a Golfer Class]]
- [[#multiple-cursor-alternative][multiple cursor alternative]]
- [[#split-line-with-dots][Split line with dots]]
- [[#switch-variable][switch variable]]
- [[#from-argument-to-object][From argument to object]]
- [[#-a-b-c-][-a-b-c-]]
- [[#attr_aligner][attr_aligner]]
- [[#triangular-numbers][Triangular Numbers]]
- [[#search-and-replace-0][Search and Replace 0]]
- [[#quotes-inside-quotes][quotes inside quotes]]
- [[#that-hyphen][That hyphen]]
- [[#simple-format-2][Simple format (2)]]
- [[#extract-argument-from-function][Extract argument from function]]
- [[#preferably-without-multi-cursor-plugin][Preferably without multi-cursor plugin]]
- [[#letterbox][Letterbox]]
- [[#adams-challenge][Adam's challenge]]
- [[#flip-the-bit][Flip the bit]]
- [[#missing-library-and-a-typo][Missing Library and a Typo]]
- [[#dont-know-what-this-is][Don't know what this is]]
- [[#real-world-php-to-markdown][Real World PHP To Markdown]]
- [[#learn-some-german-verbs][Learn some german verbs]]
- [[#replacing-each-line-of-a-block-selection][replacing each line of a block selection]]
- [[#fiddle-percentages-into-real-numbers][Fiddle percentages into real numbers]]
- [[#space-out-the-alphabet][Space out the alphabet]]
- [[#there-is-no-vertical-limit-for-vim-ninjas][There is no vertical limit for vim Ninjas]]
- [[#whitespace-empty-lines-and-tabs][Whitespace, empty lines and tabs]]
- [[#order-and-join][Order and join]]
- [[#kolakoski-sequence----level-1][Kolakoski sequence -- level 1]]
- [[#swap-the-operands-under-comparison][Swap the operands under comparison]]
- [[#saving-the-hashes][Saving the hashes(#)]]
- [[#unknown-command][unknown command]]
- [[#align-commas][Align commas]]
- [[#comments-galore][comments galore]]
- [[#switch-function-arguments][Switch function arguments]]
- [[#pascals-triangle][Pascal's Triangle]]
- [[#number-sort][Number Sort]]
- [[#letter-case-trickery][Letter case trickery]]
- [[#python-challenge][Python challenge]]
- [[#make-it-more-readable][Make it more readable]]
- [[#scrambled-numbers][Scrambled numbers]]
- [[#make-html-list][Make HTML List]]
- [[#c-reformatting][C Reformatting]]
- [[#numbering-a-list][Numbering a List]]
- [[#do-you-demand-a-shrubbery][Do you demand a shrubbery?]]
- [[#fix-the-xml][Fix the XML]]
- [[#array-transposition-1][Array Transposition]]
- [[#sfd-roc-vimvimvim][SFD-ROC: vimvimvim]]
- [[#shebangs-for-all][Shebangs for all]]
- [[#count-both-ways][Count both ways]]
- [[#mess-in-revision-history][Mess in revision history]]
- [[#mirror-symmetry][Mirror Symmetry]]
- [[#the-d-a-n-k-side-of-the-moon][The D a n k Side of the Moon]]
- [[#camel-riding][camel riding]]
- [[#array-propagate][Array propagate]]
- [[#where-should-i-put-the-newline][Where should I put the Newline?]]
- [[#hole-in-one][Hole-in-one]]
- [[#from-a-to-b][From A to B]]
- [[#remove-dupes-from-array][remove dupes from array]]
- [[#list-specification][list specification]]
- [[#santas-naughty--nice-list][Santa's naughty / nice list]]
- [[#condensed-cases][Condensed Cases]]
- [[#paragraph-breaks][Paragraph breaks]]
- [[#remember-vimgolf-rules-][Remember VimGolf Rules !]]
- [[#snowflake-fractal][snowflake fractal]]
- [[#change-the-content-of-a-string][Change the content of a string]]
- [[#alsa-configuration][Alsa configuration]]
- [[#gray-area][Gray area]]
- [[#lets-play-some-ivmgolf][Let's play some Ivmgolf]]
- [[#the-cake-is-a-lie][The Cake is a Lie]]
- [[#two-become-one][Two become one]]
- [[#create-a-table][Create a table]]
- [[#sort-and-add-attributes][Sort and add attributes]]
- [[#ruby-19-hashes][Ruby 1.9 hashes]]
- [[#append-semicolon-after-expressions][Append semicolon after expressions]]
- [[#reconstruct-the-sentence][Reconstruct the Sentence]]
- [[#simple-addition][Simple addition]]
- [[#hello-world][Hello ${world}]]
- [[#paragraph-sort][Paragraph sort]]
- [[#stairstep-digits][Stairstep digits]]
- [[#kolakoski-sequence----level-2][Kolakoski sequence -- level 2]]
- [[#nesting-sass][Nesting SASS]]
- [[#exchanging-quotes][Exchanging Quotes]]
- [[#make-fancy-header][Make Fancy Header]]
- [[#combines-all-items][Combines all items]]
- [[#a-simple-one][A Simple One]]
- [[#wrap-text-in-quotes][Wrap text in quotes]]
- [[#replace-and-keep-the-case][Replace and keep the case]]
- [[#python-hello-world-reformatting][Python Hello World! Reformatting]]
- [[#ugly-spreadsheet-copypaste-to-csv][Ugly spreadsheet copy/paste to CSV]]
- [[#flodder-challenge][Flodder-challenge]]
- [[#mute-the-second-method-of-this-script][Mute the second method of this script]]
- [[#simple-format-3][simple format (3)]]
- [[#the-name-of-the-game][The name of the game]]
- [[#interactive-git-rebase-changing-commands][Interactive git rebase changing commands]]
- [[#generate-a-list-of-numbers][Generate a list of numbers]]
- [[#remove-noise-from-http-log][Remove noise from HTTP log]]
- [[#html-to-haml][HTML to Haml]]
- [[#reverse-simple-deletion][Reverse Simple Deletion]]
- [[#assignment-alignment][Assignment Alignment]]
- [[#happy-tvvo][Happy TvvO]]
- [[#vimgolfnight][VimGolfNight]]
- [[#lisp-condense][Lisp Condense]]
- [[#text-to-html-table][Text to HTML Table]]
- [[#prefixes-and-suffixes][Prefixes and suffixes]]
- [[#swap-assigned-value][Swap assigned value]]
- [[#angular-naming-conventions][Angular naming conventions]]
- [[#replace-2nd-column-blanks-with-values-in-same-column-if-blank][replace 2nd column blanks with values in same column if blank]]
- [[#braces-or-brackets][Braces or Brackets?]]
- [[#120-degrees][120 Degrees]]
- [[#on-being-stylish][On Being Stylish]]
- [[#lamb-had-a-little-mary][lamb had a little Mary]]
- [[#minimalist-limerick][Minimalist Limerick]]
- [[#pretty-multi-line-bash][Pretty multi-line bash]]
- [[#add-to-end-of-each-line-kinda][Add to end of each line... kinda]]
- [[#readability][readability]]
- [[#line-em-up][Line 'em up!]]
- [[#the-meaning][The meaning]]
- [[#ascii-box][ASCII box]]
- [[#imports-alignment-python][imports alignment (python)]]
- [[#add-go-xml-to-structure-tags][Add Go XML to structure tags]]
- [[#separate-the-lines][Separate the lines]]
- [[#lipsum-lines][lipsum lines]]
- [[#reverse-characters-in-a-line][Reverse characters in a line]]
- [[#ruby-19-compat][Ruby 1.9 compat]]
- [[#logging-with-key][Logging with key]]
- [[#vim-tetris][Vim tetris]]
- [[#7th-birthday][7th Birthday]]
- [[#vim--22--7][vim = 22 / 7]]
- [[#remove-semicolons-after-expressions][Remove semicolons after expressions]]
- [[#counting-in-binary][Counting in binary]]
- [[#remember-fizzbuzz][Remember FizzBuzz?]]
- [[#reformat-most-common-surnames][Reformat most common surnames]]
- [[#interweave-two-blocks-of-text][Interweave two blocks of text]]
- [[#reformat-some-python][Reformat some Python]]
- [[#split-the-words][Split the words]]
- [[#shuffle-puzzle][Shuffle puzzle]]
- [[#unfinnished-work][Un"finnish"ed Work]]
- [[#reverse-and-double-space][Reverse and double space]]
- [[#nato-phonetic-alphabet][NATO phonetic alphabet]]
- [[#wrap-the-text-of-an-email-message-to-79-characters][Wrap the text of an email message to 79 characters]]
- [[#increment-increment-increment][Increment, increment, increment....]]
- [[#delete-unwanted-lines][Delete unwanted lines]]
- [[#subnetting][Subnetting]]
- [[#reformat-a-c-golf-submission][Reformat a C golf submission]]
- [[#pairs-of-numbers][Pairs of numbers]]
- [[#replacing-some-words][Replacing some words]]
- [[#stairs-indenting][Stairs Indenting]]
- [[#for-all-cases][For all cases.]]
- [[#a-simple-change][A simple change]]
- [[#php-array-syntax---mailchimp-merge-syntax][PHP Array Syntax -> MailChimp Merge Syntax]]
- [[#context-insensitive-completion-0][Context insensitive completion 0]]
- [[#sorting-paragraphs][Sorting paragraphs]]
- [[#add-fold-markers-to-a-c-file][Add fold markers to a .c file]]
- [[#sort-files-from-hosts][Sort files from hosts]]
- [[#going-underground][Going underground....]]
- [[#indentation][Indentation]]
- [[#line-zipper][Line Zipper]]
- [[#shuffled-numbers][Shuffled numbers]]
- [[#vim1001][vim1001]]
- [[#mirrored-text][Mirrored text]]
- [[#the-quick-brown-fox-jumps-over-the-lazy-vim][The Quick Brown Fox Jumps Over The Lazy Vim]]
- [[#generate-english-alphabets][Generate English Alphabets]]
- [[#youre-stuck-on-jquery--17][you're stuck on jQuery < 1.7]]
- [[#case-preserving-word-replacement][Case preserving word replacement]]
- [[#foodcritic023-prefer-conditional-attributes][FoodCritic023: Prefer conditional attributes]]
- [[#start-coding-format][Start coding format]]
- [[#context-insensitive-completion-1][Context Insensitive completion 1]]
- [[#insert-a-markdown-link][Insert a Markdown link]]
- [[#nbcu-weekly-challenge---test][NBCU Weekly Challenge - Test]]
- [[#reverse-and-count][Reverse and count]]
- [[#sorting-database-text-output][Sorting database text output]]
- [[#underscore_to_camelcase][underscore_to_camelCase]]
- [[#js-notation-to-immutablejs-notation][JS notation to Immutable.js notation]]
- [[#hatsuyume][Hatsuyume]]
- [[#vims-not-included-features][Vim's not included features]]
- [[#rotating-philosophers-problem][Rotating Philosophers Problem]]
- [[#sort-the-vimgolf-challenges-by-popularity][Sort the VimGolf challenges by popularity]]
- [[#array-of-characters][Array of characters]]
- [[#a-grid-of-punctuation][A grid of punctuation]]
- [[#sort-entries-based-on-date][Sort entries based on date]]
- [[#happy-new-year][Happy New Year!]]
- [[#restore-order-to-the-alphabet][Restore order to the alphabet]]
- [[#neither-fizz-nor-buzz][Neither Fizz nor Buzz]]
- [[#learn-vim-in-short-time][learn vim in short time]]
- [[#refactor-static-member-invocation][Refactor static member invocation]]
- [[#table-reshuffle][Table Reshuffle]]
- [[#reformat-long-lines][Reformat long lines]]
- [[#abcd--a-b-c-d][abcd > a b c d]]
- [[#shift-down][Shift down]]
- [[#get-rid-of-html-tags][Get rid of html tags]]
- [[#change-attribute-to-getter][Change attribute to getter]]
- [[#remove-all-lines-in-first-part][remove all lines in first part]]
- [[#wget-failed-to-download-redirections][Wget failed to download redirections]]
- [[#free-hyphen][Free hyphen!]]
- [[#the-holy-grail-may-help][The holy-grail may help]]
- [[#inner-hyphens][Inner hyphens]]
- [[#readable-rubyhash][Readable Rubyhash]]
- [[#suffix-sort][Suffix sort]]
- [[#create-leading-zeros][Create Leading Zeros]]
- [[#enumerate-words][Enumerate words]]
- [[#number-an-outline][Number an outline]]
- [[#create-arrows-in-a-list][create arrows in a list]]
- [[#compile-c][Compile C]]
- [[#alphabetize-the-directory][Alphabetize the directory]]
- [[#allen-taylor][Allen, Taylor]]
- [[#deleting-folded-text][Deleting folded text]]
- [[#vim-set-foldmethodmarker-][vim: set foldmethod=marker: */]]
- [[#extract-html-option-values-from-tag-values][Extract HTML option values from tag values]]
- [[#increment-by-column-in-xml][increment by column in XML]]
- [[#sorting-a-glossary][Sorting a glossary]]
- [[#prime-numbers][Prime Numbers]]
- [[#word-frequency-alignment][Word frequency alignment]]
- [[#subtraction][Subtraction]]
- [[#format-java-properties][Format java properties]]
- [[#top-x][Top X]]
- [[#interleave-lines][Interleave lines]]
- [[#change-name-of-a-variable][Change name of a variable]]
- [[#fix-the-haiku][Fix the Haiku]]
- [[#82-bottles-of-beer-on-the-wall][82 bottles of beer on the wall]]
- [[#expand-a-list-comprehension-python][expand a list comprehension (python)]]
- [[#pretty-format-for-variable-declarations][Pretty format for variable declarations]]
- [[#round-round][Round Round]]
- [[#python-to-ruby][Python to Ruby]]
- [[#recursively-palindrome][Recursively Palindrome]]
- [[#cleanining-up-80-column-concatenated-text][Cleanining up 80 column concatenated text]]
- [[#manual-sql][Manual SQL]]
- [[#parsing-with-csv-unify-lines-and-result][Parsing with CSV: Unify lines and result.]]
- [[#sort-the-cardinal-numbers][Sort the cardinal numbers]]
- [[#java-array2list][Java Array2List]]
- [[#back-to-the-roots][Back to the roots]]
- [[#test-everything][Test everything!]]
- [[#fun-with-the-diagonal][Fun With The Diagonal]]
- [[#nbcu-weekly-challenge---0][NBCU Weekly Challenge - #0]]
- [[#refactor-arguments-into-object-argument][Refactor arguments into object argument]]
- [[#shuffle-and-sort][Shuffle and Sort]]
- [[#assign-list][Assign list]]
- [[#winning-streak][Winning streak]]
- [[#block-fun-1][Block Fun 1]]
- [[#cartesian-product][Cartesian product]]
- [[#hidden-message][Hidden Message]]
- [[#generate-fibonacci-numbers][Generate Fibonacci Numbers]]
- [[#another-mixed-up-haiku][Another Mixed-Up Haiku]]
- [[#itss-tooo-coold-too-typpe-todaay][It'ss tooo coold too typpe todaay]]
- [[#dehamlizing][Dehamlizing]]
- [[#php----java-class-conversion-part-1][PHP <--> Java class conversion Part 1]]
- [[#separating-firstname--lastname][Separating firstname & lastname]]
- [[#assign-numbers-to-fields][Assign numbers to fields]]
- [[#piphilology][Piphilology]]
- [[#swap-or-reverse][swap or reverse]]
- [[#constructor][constructor]]
- [[#aligning-function-arguments-to-match-a-specific-coding-style][Aligning function arguments to match a specific coding style]]
- [[#formatted-text-to-markdown][formatted text to markdown]]
- [[#ascii-art][ASCII Art]]
- [[#turn-this-csv-list-into-queries][Turn this csv list into queries]]
- [[#complete-the-hex-array-data][Complete the hex array data]]
- [[#multiplication-table][Multiplication table.]]
- [[#sfd-roc-the-quick-brown-fox][SFD-ROC: The Quick Brown Fox]]
- [[#groups-magic][Groups magic]]
- [[#unwrap-the-text-of-an-email-message][Unwrap the text of an email message]]
- [[#redrum][REDRUM]]
- [[#long-prime-list---filter-version][Long prime list - filter version]]
- [[#inconsistent-real-estate-paste][Inconsistent real estate paste]]
- [[#winding-path][Winding path]]
- [[#circle-in-a-square][Circle in a square]]
- [[#42-header][42-header]]
- [[#create-a-pandoc-compatible-table][Create a pandoc compatible table]]
- [[#almost-encrypted][Almost encrypted]]
- [[#convert-pandoc-unordered-list-to-a-numbered-list][Convert pandoc unordered list to a numbered list]]
- [[#solve-the-sokoban][Solve the Sokoban]]
- [[#sfd-roc-tic-tac-toe][SFD-ROC: Tic-Tac-Toe]]
- [[#entries-sort][Entries sort]]
- [[#pep8-python-wrapping-comments-and-code][PEP8 Python Wrapping Comments and Code]]
- [[#o-christmas-tree][O Christmas Tree]]
- [[#sort-yaml-structures-alphabetically-by-root-key-names][Sort yaml structures alphabetically by root key names]]
- [[#draw-the-go-board][Draw the Go board]]
- [[#define-to-require][Define to require]]
- [[#refactoring-useless-method-away][Refactoring useless Method away]]
- [[#turn-a-ninja-to-case-insensitive][Turn a ninja to case-insensitive...]]
- [[#csv-to-json][CSV to JSON]]
- [[#getters--setters-java][Getters & Setters: Java]]
- [[#fill-visual-area][Fill visual area]]
- [[#overall-vimgolf-rank][Overall Vimgolf Rank]]
- [[#write-setters-and-getters-for-php][Write Setters and Getters for PHP]]
- [[#checkerboard-case-pattern][Checkerboard case pattern]]
- [[#changing-url-path-in-css][Changing URL path in CSS]]
- [[#extract-text-from-xml][Extract text from xml]]
- [[#happy-new-year-1][Happy New Year!]]
- [[#complete-the-hex-array-data-part-ii][Complete the hex array data (Part II)]]
- [[#the-universal-declaration-of-human-rights-article-1][The Universal Declaration of Human Rights, Article 1]]
- [[#rail-fence-transposition-cipher][Rail fence transposition cipher]]
- [[#sudoku-table][Sudoku table]]
- [[#calculate-the-table-totals][Calculate the table totals]]
- [[#double-and-switch][Double and switch]]
- [[#ninjas-leaderboard][Ninjas Leaderboard]]
- [[#printable-ascii-characters][Printable ASCII characters]]
- [[#letters-are-numbers][Letters are numbers]]
- [[#land-of-the-lost][Land of the Lost]]
- [[#comparing-scores][Comparing scores]]
- [[#word-blender][Word Blender]]
- [[#format-the-output][Format the output]]
- [[#replace-parameter-with-explicit-methods][Replace Parameter with Explicit Methods]]
- [[#square-numbers][Square numbers]]
- [[#converting-group-lines-from-format-a-to-format-b][Converting group lines from format A to Format B]]
- [[#flatten-repo][Flatten repo]]
- [[#paste-indent-correction---js][paste indent correction - JS]]
- [[#linear-congruential-generator][Linear congruential generator]]
- [[#roman-numerals][Roman numerals]]
- [[#its-a-factor][It's a factor]]
- [[#remove-accent-off-the-letter][Remove Accent off the Letter]]
- [[#html-formatting-vertical-alignment-for-readability][HTML formatting: vertical alignment for readability]]
- [[#sierpinskis-triangle][Sierpinski's Triangle]]
- [[#execute-immediate-sql][Execute immediate SQL]]
- [[#lower-cased-and-dashed-strings][Lower cased and dashed strings]]
- [[#create-an-alphabet-diamond][Create an alphabet diamond]]
- [[#before-there-was-farmville][Before there was Farmville...]]
- [[#chucking-wood][Chucking wood]]
- [[#php----java-class-conversion-part-2][PHP <--> Java class conversion Part 2]]
- [[#complete-the-circuit-grid][Complete the circuit grid!]]
- [[#not-enough-ps][Not enough Ps]]
- [[#sfd-roc-rot13-phonics][SFD-ROC: ROT13 Phonics]]
- [[#make-the-circuit-grid][Make the circuit grid!]]
- [[#sql-to-yaml][SQL to YAML]]
- [[#transposition][Transposition]]
- [[#lookahead-and-lookbehind][Lookahead and Lookbehind]]
- [[#python-lots-of-function-arguments][Python: Lots of function arguments]]
- [[#flip-the-chessboard][Flip the chessboard]]
- [[#permutations-n4][Permutations N=4]]
- [[#harder-than-abcd--a-b-c-d][Harder than "abcd > a b c d"]]
- [[#sfd-roc-ascii-logo-border][SFD-ROC: ASCII Logo Border]]
- [[#ascii-art-diamond][ascii-art diamond]]
- [[#hanging-indent-for-footnotes][Hanging Indent for Footnotes]]
- [[#dumb-to-smart][Dumb to smart]]
- [[#create-bison-tokens][Create bison tokens]]
- [[#tiny-column-alignment][Tiny column alignment]]
- [[#sort-python-functions-and-methods-alphabetically][sort python functions and methods alphabetically]]
- [[#sort-functions-in-the-python-file-alphabetically--sort-functions-within-a-class-alphabetically--sort-classes-alphabetically][sort functions in the python file alphabetically * sort functions within a Class alphabetically * sort Classes alphabetically]]
- [[#greek-column-realign][Greek column realign]]
- [[#remove-hard-line-breaks][Remove hard line breaks]]
- [[#circle-of-fifths-with-sharps][Circle of Fifths with Sharps]]
- [[#add-links-to-an-existing-html-table][Add links to an existing HTML table]]
- [[#here-piggy-piggy][Here, piggy, piggy...]]
- [[#binary-and-increment][Binary and Increment]]
- [[#c-to-vimdict][C to VimDict]]
- [[#json-string-rotation][JSON string rotation]]
- [[#recursive-cowsay][Recursive Cowsay]]
- [[#return-the-cow][Return the cow]]
- [[#tar-archive-pretty-print][TAR archive pretty print]]
- [[#five-pillars][Five Pillars]]
- [[#mp3---cutlist][mp3 - Cutlist]]
- [[#chinese-multiplication-table][Chinese Multiplication Table]]
- [[#carriage-return][Carriage return]]
- [[#enharmonic-equivalents][Enharmonic Equivalents]]
- [[#untangle-my-tail-please][Untangle my tail, please!]]
- [[#coordinates-placeholder][Coordinates placeholder]]
- [[#merge-blank-lines-and-properly-capitalize][Merge blank lines and properly capitalize]]
- [[#convert-regular-pandoc-footnotes-to-in-line-notes][Convert regular pandoc footnotes to in-line notes]]
- [[#un-c-escape-string][un-C-escape string]]
- [[#across-down-flip][Across-Down Flip]]
- [[#extended-customer-2][Extended Customer 2]]
- [[#sort-by-sum-of-numbers-in-a-line][Sort by sum of numbers in a line(?)]]
- [[#presidential-sorting][Presidential Sorting]]
- [[#lenny-spiral][Lenny Spiral]]
- [[#maximun-and-minimun][maximun and minimun]]
- [[#simple-maths][Simple Maths]]
- [[#under-the-cupola][Under the cupola]]
- [[#sort-by-your-own-sum][Sort by your own sum]]
- [[#xml-to-json][XML to JSON]]
- [[#fibonacci-triangles][Fibonacci Triangles]]
- [[#range10-digit-rotation][range(10) digit rotation]]
- [[#sort-with-uniq-openembedded-package-names][Sort with uniq OpenEmbedded package names]]
- [[#greek-letters][Greek Letters]]
- [[#maze-path][Maze path]]
- [[#change-the-perspective][Change The Perspective]]
- [[#refactor-to-helpers][Refactor to Helpers]]
- [[#my-cafe-needs-a-new-menu][My cafe needs a new menu]]
- [[#palindrome-numbers][Palindrome numbers]]
- [[#50-factorials-mod-97][50 factorials mod 97]]
- [[#config-sections][Config Sections]]
- [[#199-fibonacci-numbers][199 Fibonacci Numbers]]
- [[#latex-to-xml-math-delimiters][LaTeX to XML Math Delimiters]]
- [[#custom-mccarthy-sequence][Custom McCarthy sequence]]
- [[#hail-to-alekseï-pajitnov][Hail to Alekseï Pajitnov]]
- [[#acute-accents][Acute accents]]
- [[#convert-pasted-text-into-markdown][Convert pasted text into Markdown]]
- [[#forgot-to-follow-the-naming-convention][Forgot to follow the naming convention...]]
- [[#no-naked-if-allowed][No naked if allowed!]]
- [[#conway-sequence][Conway sequence]]
- [[#splits-long-lines-in-more-readable-ones][Splits long lines in more readable ones]]
- [[#turn-the-x][Turn the x]]
- [[#rural-post][Rural Post]]
- [[#satisfy-the-go-linter][Satisfy the go linter]]
- [[#prepend--to-every-non-blank-line][prepend * to every non-blank line]]
- [[#add-semicolons][Add semicolons]]
- [[#yo-to-hello][Yo To Hello]]
- [[#xrandr-outputs-and-dashes][xrandr outputs and dashes]]
- [[#multiline-to-single-line][Multiline to Single Line]]
- [[#format-the-css][Format the CSS]]
- [[#replace-pattern-with-1-2-3--on-each-line][Replace pattern with 1, 2, 3, ... on each line]]
- [[#from-a-thunderlink-to-a-markdown-link][From a Thunderlink to a Markdown link]]
- [[#line-under-headers][Line under headers]]
- [[#quote-modules][Quote modules]]
- [[#levenshtein-distance][Levenshtein distance]]
- [[#get-mail-address-from-outlook-format][Get mail address from outlook format]]
- [[#hogwarts-email-sorting][Hogwarts Email Sorting]]
- [[#data-reformat][Data reformat]]
- [[#aliases-for-cd][Aliases for cd]]
- [[#screaming_snake_case-to-title-case][SCREAMING_SNAKE_CASE to Title Case]]
- [[#reorder-the-groups][Reorder the groups]]
- [[#alphabet-soup][Alphabet soup]]
- [[#add-string-initializers-to-an-enum][Add string initializers to an enum]]
- [[#unsemantic-linewrapping][Unsemantic linewrapping]]
- [[#add-quotes-to-ansible-playbook][Add quotes to ansible playbook]]
- [[#just-the-middle][Just the middle]]
- [[#bad-copy-syntax][Bad Copy Syntax]]
- [[#html-paragraph-to-table][html paragraph to table]]
- [[#reconstruct-the-actual-output-from-my-unit-test-tool-report][Reconstruct the actual output from my unit test tool report]]
- [[#refactor-typescript-arrow-function-type][Refactor typescript arrow function type]]
- [[#c-data-class-to-f-record][C# data class to F# record]]
- [[#vertical-limit][Vertical Limit]]
- [[#ascii-art-histogram][ASCII-art Histogram]]
- [[#quote-modules-ver2][Quote modules (ver.2)]]
- [[#add-text-at-some-column][Add text at some column]]
- [[#calculations][calculations]]
- [[#change-parenthesis][change parenthesis]]
- [[#song-transcription-oops][Song Transcription Oops]]
- [[#remove-quotes-after-first-field][Remove quotes after first field]]
- [[#join-em][Join 'em]]
- [[#extract-wireshark-capture-filter][Extract wireshark capture filter]]
- [[#triangle-of-arrows][Triangle of arrows]]
- [[#around-the-clock][Around the clock]]
- [[#right-align-part-of-the-line][Right Align Part of the line]]
- [[#add-line-and-index][add line and index]]
- [[#reformat-cura-settings][Reformat Cura settings]]
- [[#change-your-calendar][Change your calendar]]
- [[#hash-staircase][Hash staircase]]
- [[#start-coding-format-1][Start coding format]]
- [[#if-then-else-regexp][If-then-else regexp]]
- [[#create-leading-zeros-1][Create Leading Zeros]]
- [[#rule-110][Rule 110]]
- [[#c-function-to-f][C# function to F#]]
- [[#real-world-php-to-markdown-1][[Real World] PHP To Markdown]]
- [[#citizen_hacks_2019_part6][citizen_hacks_2019_part6]]
- [[#label-grid-cells-6x6][Label grid cells (6x6)]]
- [[#citizen_hacks_2019_challenge1][citizen_hacks_2019_challenge1]]
- [[#citizen_hacks_2019_challenge2][citizen_hacks_2019_challenge2]]
- [[#citizen_hacks_2019_challenge3][citizen_hacks_2019_challenge3]]
- [[#citizen_hacks_2019_challenge5][citizen_hacks_2019_challenge5]]
- [[#citizen_hacks_2019_challenge6][citizen_hacks_2019_challenge6]]
- [[#citizen_hacks_2019_part1][citizen_hacks_2019_part1]]
- [[#citizen_hacks_2019_part2][citizen_hacks_2019_part2]]
- [[#citizen_hacks_2019_part3][citizen_hacks_2019_part3]]
- [[#citizen_hacks_2019_part4][citizen_hacks_2019_part4]]
- [[#citizen_hacks_2019_part9][citizen_hacks_2019_part9]]
- [[#letters-are-numbers-1][Letters are numbers]]
- [[#sfd-roc-pipe-dreams][SFD-ROC: Pipe Dreams]]
- [[#fibc-cleanup][fib.c cleanup]]
- [[#back-to-the-future][Back to the Future]]

* Box it
Create a box around a line.

** Start file
#+BEGIN_SRC 
My dream is to be in a box
#+END_SRC

** End file

#+BEGIN_SRC 
###############################
# My dream was to be in a box #
###############################
#+END_SRC

* Simple, Practical, and Common

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way." This challenge is just a simple movement and entering text at a certain place.
** Start file
#+BEGIN_SRC 
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

This challenge is just a simple movement and entering text at a certain place.
#+END_SRC

** End file

#+BEGIN_SRC 
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0
*temp var7 11

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

New text.

This challenge is just a simple movement and entering text at a certain place.
#+END_SRC

* ninja substitution

How can you reuse a previous substitution ?
** Start file
#+BEGIN_SRC 
Trying to careninjafully make a ninja challenge.
This ninjaninjachallenge is ninjadesigned to show a particularninja vim ninjafeature (here I am ninjastalling in order to ninjadoge a shorter ninjacounter-based ninjasolution, sorry for the ninjaheadhache) this is the end of my ninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjalninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaininjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjanninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaeninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninjaninja.
The question is, will a wiser vimgolf ninja defeat the purpose of this challenge ?
#+END_SRC

** End file

#+BEGIN_SRC 
Trying to carefully make a ninja challenge.
This challenge is designed to show a particular vim feature (here I am stalling in order to doge a shorter counter-based solution, sorry for the headhache) this is the end of my line.
The question is, will a wiser vimgolf ninja defeat the purpose of this challenge ?
#+END_SRC

* simple format

make it look better.
** Start file
#+BEGIN_SRC 
one:1
two:2
three:3
four:4
five:5
six:6
seven:7
eight:8
nine:9
ten:10
#+END_SRC

** End file
#+BEGIN_SRC 
  "one":1
  "two":2
"three":3
 "four":4
 "five":5
  "six":6
"seven":7
"eight":8
 "nine":9
  "ten":10
#+END_SRC

* One number per line

Just give me the numbers.
** Start file
#+BEGIN_SRC 
- One number per line -
-----------------------
2,3,5,7,
11,13,17,
19,23,29,
#+END_SRC

** End file
#+BEGIN_SRC 
2
3
5
7
11
13
17
19
23
29
#+END_SRC

* remove lines containing the word "reader"

easy stuff
** Start file
#+BEGIN_SRC 
aklfdjwi37u8rifa a8fdiy 8837r asfyf3y reader
ksaldfjlasreadr aodifufjoe readddddddrrfai 
lakdfj0923898 928329 192378 reader
213891823 reader 29083190283 893774701283
https://website.grep/reader/somecomic.cbz
https://website.ls/download/somecomic.cbz
reader
not reader
#+END_SRC

** End file
#+BEGIN_SRC 
ksaldfjlasreadr aodifufjoe readddddddrrfai 
https://website.ls/download/somecomic.cbz
#+END_SRC

* One to Ten

Generate the sequence of numbers from 1 to 10, one number per line. Inspired by this Reddit thread: https://redd.it/ak4it2
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
3
4
5
6
7
8
9
10
#+END_SRC

* Two pairs of cluster of letters creates word

Clean and group.
** Start file
#+BEGIN_SRC 
't', 'wo', 'pa','irs', 'o', 'f','clus','ter', 'o', 'f', 'lett', 'ers', 'crea', 'tes', 'wor','d'
#+END_SRC

** End file
#+BEGIN_SRC 
two
pairs
of
cluster
of
letters
creates
word
#+END_SRC

* I forgot quotes

Oops.
** Start file
#+BEGIN_SRC 
foo = a
      ab
      abc
#+END_SRC

** End file
#+BEGIN_SRC 
foo = "a"
      "ab"
      "abc"
#+END_SRC

* Applying same text modification in several lines

Remove identical text at the beginning of several lines and the closing parenthesis.
** Start file
#+BEGIN_SRC 
Assert.ThrowsAsync<Exception>(() => _auction.StartSellingItem());
Assert.ThrowsAsync<Exception>(() => _application.StartBiddingIn(_auction));
Assert.ThrowsAsync<Exception>(() => _auction.HasReceivedJoinRequestFromSniper());
Assert.ThrowsAsync<Exception>(() => _auction.AnnounceClosed());
Assert.ThrowsAsync<Exception>(() => _application.ShowsSniperHasLostAuction());
#+END_SRC

** End file
#+BEGIN_SRC 
_auction.StartSellingItem();
_application.StartBiddingIn(_auction);
_auction.HasReceivedJoinRequestFromSniper();
_auction.AnnounceClosed();
_application.ShowsSniperHasLostAuction();
#+END_SRC

* Cool or not?

abc trying to be cool or not...
** Start file
#+BEGIN_SRC 
This is abc.
This is also abc.
This abc is cool.
This abc is so cool.
This is a simple abc.
This isn't a cool abc.
This abc is not as cool as used to be.
This abc really is cool.
This abc is not so cool
I finally found a real abc.
#+END_SRC

** End file
#+BEGIN_SRC 
This is abc.
This is also abc.
This abcool is cool.
This abcool is so cool.
This is a simple abc.
This isn't a cool abc.
This abc is not as cool as used to be.
This abcool really is cool.
This abc is not so cool
I finally found a real abc.
#+END_SRC

* Leave only the numbered lines.
** Start file
#+BEGIN_SRC 
Leave only the
numbered lines.
LINE 1
LINE 2
LINE 3
That's all.
Thank you
very much.
#+END_SRC

** End file
#+BEGIN_SRC 
LINE 1
LINE 2
LINE 3
#+END_SRC

* Com(m)a Trouble

Someone was real stupid when placing his commas. Can you fix it?
** Start file
#+BEGIN_SRC 
,0,1,2,3,4,5,6,7,89
,1,2,3,4,5,6,7,8,90
,2,3,4,5,6,7,8,9,01
,3,4,5,6,7,8,9,0,12
,4,5,6,7,8,9,0,1,23
56,7,8,9,0,1,2,3,4,
67,8,9,0,1,2,3,4,5,
78,9,0,1,2,3,4,5,6,
89,0,1,2,3,4,5,6,7,
90,1,2,3,4,5,6,7,8,
#+END_SRC

** End file
#+BEGIN_SRC 
0,1,2,3,4,5,6,7,8,9
1,2,3,4,5,6,7,8,9,0
2,3,4,5,6,7,8,9,0,1
3,4,5,6,7,8,9,0,1,2
4,5,6,7,8,9,0,1,2,3
5,6,7,8,9,0,1,2,3,4
6,7,8,9,0,1,2,3,4,5
7,8,9,0,1,2,3,4,5,6
8,9,0,1,2,3,4,5,6,7
9,0,1,2,3,4,5,6,7,8
#+END_SRC

* Words in parens

We should all ace this, right?
** Start file
#+BEGIN_SRC 
one two
three
#+END_SRC

** End file
#+BEGIN_SRC 
(one) (two)
(three)
#+END_SRC

* Swap values inside brackets

Easy challenge.
** Start file
#+BEGIN_SRC 
#Everyday routine... :\ 

amazing_func("Some amazing text", 123, variable) # Kittens

def func():
        return 'Stuff for making movement harder'

def func2(m):
        v = 0
        for i in range(10):
                v += i*m
                print(v, i, m)

very_strange_func(42, foobar, 'Another text') # Dogs

test = func()
func2(len(test))
#+END_SRC

** End file
#+BEGIN_SRC 
#Everyday routine... :\ 

amazing_func(42, foobar, 'Another text') # Kittens

def func():
        return 'Stuff for making movement harder'

def func2(m):
        v = 0
        for i in range(10):
                v += i*m
                print(v, i, m)

very_strange_func("Some amazing text", 123, variable) # Dogs

test = func()
func2(len(test))
#+END_SRC

* A HAPPY NEW YEAR 2014 !

A HAPPY NEW YEAR 2014 !
** Start file
#+BEGIN_SRC 
A HAPPY END WITH YEAR 2013 !
#+END_SRC

** End file
#+BEGIN_SRC 
A HAPPY NEW YEAR 2014 !
#+END_SRC

* Increment each number

Increment each number individually by one
** Start file
#+BEGIN_SRC 
10794586310243795
#+END_SRC

** End file
#+BEGIN_SRC 
21805697421354806
#+END_SRC

* Vice versa

Little role switching.
** Start file
#+BEGIN_SRC 
The quick brown fox jumps over the lazy dog.
#+END_SRC

** End file
#+BEGIN_SRC 
The quick lazy dog jumps over the brown fox.
#+END_SRC

* Resort and deup a CSV list

I'm always adding items to a sorted list. There has to be a better way dedup and resort the lists. There are multiple lists with varying lengths to discourage manual sorting. Also Australia's animals are weird.
** Start file
#+BEGIN_SRC 
// Animals ordered by continent.
africa = ["hippo", "lion", "atlas bear", "gorilla", "hyena", "giraffe", "zebra"]
asia = ["tiger", "honey bear", "yak", "monkey", "panda"]
europe = ["flea", "brown bear", "ox", "fox", "rat", "deer"]
namerica = ["polar bear", "alligator", "cougar", "wolf", "bison", "reindeer", "raccoon"]
samerica = ["puma", "anaconda", "llama", "capybara", "spectacled bear", "penguin", "sloth"]
australia = ["crocodile", "SPIDERS!", "dingo", "SPIDERS!", "kangaroo", "spider bear", "playtpus", "koala", "SPIDERS!", "echidna"]
#+END_SRC

** End file
#+BEGIN_SRC 
// Animals ordered by continent.
africa = ["atlas bear", "giraffe", "gorilla", "hippo", "hyena", "lion", "zebra"]
asia = ["honey bear", "monkey", "panda", "tiger", "yak"]
europe = ["brown bear", "deer", "flea", "fox", "ox", "rat"]
namerica = ["alligator", "bison", "cougar", "polar bear", "raccoon", "reindeer", "wolf"]
samerica = ["anaconda", "capybara", "llama", "penguin", "puma", "sloth", "spectacled bear"]
australia = ["SPIDERS!", "crocodile", "dingo", "echidna", "kangaroo", "koala", "playtpus", "spider bear"]
#+END_SRC

* Delete to the end of the current line

Delete to the end of the current line, but keep the character under the cursor.
** Start file
#+BEGIN_SRC 
just to remove all text after; // this is a comment
#+END_SRC

** End file
#+BEGIN_SRC 
just to remove all text after;
#+END_SRC

* Simple text editing with Vim

Make the pairs of lines match up by making each second line same as first
** Start file
#+BEGIN_SRC 
Make the pairs of lines match up by making each second line same as first:

# Appending text:
The name "Vim" is an acronym for "Vi IMproved"
The name "Vim" is an acronym for

# Editing text:
Vim is a text editor originally released by Bram Moolenaar in 1991 for the Amiga
Trivia: Vim is a text editor released by Bram Moolenaar in 1991 for the Amiga

# Deleting text:
Vim has a vi compatibility mode
Vim has a vi compatibility mode but when not in this mode Vim has many enhancements over vi
#+END_SRC

** End file
#+BEGIN_SRC 
Make the pairs of lines match up by making each second line same as first:

# Appending text:
The name "Vim" is an acronym for "Vi IMproved"
The name "Vim" is an acronym for "Vi IMproved"

# Editing text:
Vim is a text editor originally released by Bram Moolenaar in 1991 for the Amiga
Vim is a text editor originally released by Bram Moolenaar in 1991 for the Amiga

# Deleting text:
Vim has a vi compatibility mode
Vim has a vi compatibility mode
#+END_SRC

* Swap values

Well, swap the values...
** Start file
#+BEGIN_SRC 
name=www-data, groups=developer
#+END_SRC

** End file
#+BEGIN_SRC 
name=developer, groups=www-data
#+END_SRC

* Put the months in order

Our contractor thought that months should be in alphabetical order. Put them in calendar order please.
** Start file
#+BEGIN_SRC 
April
August
December
February
January
July
June
March
May
November
October
September
#+END_SRC

** End file
#+BEGIN_SRC 
January
February
March
April
May
June
July
August
September
October
November
December
#+END_SRC

* Change part of a function name in multiple occurrences

Change the middle part of the function name in multiple places, preferably using the next and dot commands.
** Start file
#+BEGIN_SRC 
call_this_function()

_this_
  
  call_this_function()

 _this_

 call_this_function()
#+END_SRC

** End file
#+BEGIN_SRC 
call_that_function()

_this_
  
  call_that_function()

 _this_

 call_that_function()
#+END_SRC

* Basic renumbering

Renumbering Basic.
** Start file
#+BEGIN_SRC 
10 PRINT "The actual"
15 PRINT "code doesn't"
16 PRINT "really matter."
20 PRINT "Just take"
25 PRINT "care of"
30 PRINT "the numbers."
#+END_SRC

** End file
#+BEGIN_SRC 
10 PRINT "The actual"
20 PRINT "code doesn't"
30 PRINT "really matter."
40 PRINT "Just take"
50 PRINT "care of"
60 PRINT "the numbers."
#+END_SRC

* move titles next to url, in quotes

had trouble with something similar
** Start file
#+BEGIN_SRC 
https://www.loremipsumdolor.com/atom.xml
https://www.sitametconsectetur.com/rss.xml
https://www.adipiscingelit.com/rss.xml
https://www.integerlacusenim.com/feed.xml
https://www.efficituraceleifendin.com/atom.xml

Lorem Ipsum Dolor
Sit Amet Consectetur
Adipiscing Elit
Integer Lacus Enim
Efficitur ac Eleifend In
#+END_SRC

** End file
#+BEGIN_SRC 
https://www.loremipsumdolor.com/atom.xml "Lorem Ipsum Dolor"
https://www.sitametconsectetur.com/rss.xml "Sit Amet Consectetur"
https://www.adipiscingelit.com/rss.xml "Adipiscing Elit"
https://www.integerlacusenim.com/feed.xml "Integer Lacus Enim"
https://www.efficituraceleifendin.com/atom.xml "Efficitur ac Eleifend In"
#+END_SRC

* Team names

The team names are misspelled.
** Start file
#+BEGIN_SRC 
imalayasH
gleEa
Team Owl
#+END_SRC

** End file
#+BEGIN_SRC 
Eagle
Himalayas
Owl
#+END_SRC

* Collect List

Convert to comma separated list.
** Start file
#+BEGIN_SRC 
 * item1
 * item2
 * item3
 * item4
 * item5
#+END_SRC

** End file
#+BEGIN_SRC 
item1,item2,item3,item4,item5
#+END_SRC

* convert yml into java pojo field

How fast vim can create fields for java pojo i.e class declaration referring to a (simple) yml file
** Start file
#+BEGIN_SRC 
- browser: Chrome
  browserVersion: 63
  os: window7
  osVersion: 2012
  lang: en
#+END_SRC

** End file
#+BEGIN_SRC 
private String browser;
private String browserVersion;
private String os;
private String osVersion;
private String lang;
#+END_SRC

* Array transposition

Transpose two arrays into one.
** Start file
#+BEGIN_SRC 
[1,2,3,4,5,6,7,8,9,0]
[a,b,c,d,e,f,g,h,i,j]
#+END_SRC

** End file
#+BEGIN_SRC 
[1,a,2,b,3,c,4,d,5,e,6,f,7,g,8,h,9,i,0,j]
#+END_SRC

* V to the i

Input is 99 V's. Output is 100 i's.
** Start file
#+BEGIN_SRC 
VVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVV
#+END_SRC

** End file
#+BEGIN_SRC 
iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii
#+END_SRC

* Convert Application Output to CSV

Change the application output to comma-separated values
** Start file
#+BEGIN_SRC 
app0
Duration: 15.132700ms

app1
Duration: 5346.12
Duration: 5342.3
Duration: 5614.1
Duration: 5884.18
Duration: 6082.06
Duration: 6087.21
Duration: 6140.46
Duration: 6392.49
Duration: 6484.61
Duration: 6532.93
Duration: 6488.43
Duration: 6596.62
Duration: 6650.43
Duration: 6620.47
Duration: 6740.71
Duration: 6788.45
Duration: 6888.99
Duration: 6980.85
Duration: 7032.83
Duration: 7158.24

app2
Duration: 1593.513900ms
Duration: 1627.548200ms
Duration: 1730.158700ms
Duration: 1875.952200ms
Duration: 1994.924800ms
Duration: 1991.495500ms
Duration: 2033.253300ms
Duration: 2037.780900ms
Duration: 2100.084100ms
Duration: 2219.649200ms
Duration: 2254.433100ms
Duration: 2315.607200ms
Duration: 2341.889600ms
Duration: 2360.516200ms
Duration: 2455.441300ms
Duration: 2475.084500ms
Duration: 2467.874600ms
Duration: 2493.176800ms
Duration: 2620.560300ms
Duration: 2643.711300ms

app3
Duration: 228674.570000ms
Duration: 234573.058400ms
Duration: 234685.368400ms
Duration: 240430.919200ms
Duration: 240449.140500ms
Duration: 240464.735900ms
Duration: 241006.109200ms
Duration: 241266.764500ms
Duration: 242687.977900ms
Duration: 247221.387100ms
Duration: 251116.524200ms
Duration: 251368.006600ms
Duration: 252059.346400ms
Duration: 252683.261600ms
Duration: 252686.836400ms
Duration: 252821.560100ms
Duration: 252967.342700ms
Duration: 253142.340500ms
Duration: 253627.178100ms
Duration: 253641.482200ms

app4
Duration: 258235.929600ms
Duration: 258292.169500ms
Duration: 262354.157100ms
Duration: 262716.808400ms
Duration: 262769.102100ms
Duration: 265074.881200ms
Duration: 265207.596500ms
Duration: 269306.980100ms
Duration: 273817.034800ms
Duration: 275188.636700ms
Duration: 275542.901300ms
Duration: 275956.272700ms
Duration: 276682.766500ms
Duration: 277628.021500ms
Duration: 277992.577300ms
Duration: 278193.831400ms
Duration: 278586.871400ms
Duration: 279097.451300ms
Duration: 279445.274900ms
Duration: 279500.901900ms
#+END_SRC

** End file
#+BEGIN_SRC 
app0,15
app1,5346
app2,1593
app3,228674
app4,258235
#+END_SRC

* Every other line

AaAaAaA
** Start file
#+BEGIN_SRC 
aaaaaaa
aaaaaaa
aaaaaaa
aaaaaaa
aaaaaaa
#+END_SRC

** End file
#+BEGIN_SRC 
AaAaAaA
aaaaaaa
AaAaAaA
aaaaaaa
AaAaAaA
#+END_SRC

* Build a six

Just enjoy building "a" floors...
** Start file
#+BEGIN_SRC 
6
#+END_SRC

** End file
#+BEGIN_SRC 
     a = 1
    aa = 2
   aaa = 3
  aaaa = 4
 aaaaa = 5
aaaaaa = 6
#+END_SRC

* Copy three lines

If the site is up (by some miracle), make the text under every header identical.
** Start file
#+BEGIN_SRC 
First:
        Junk text.
Second:
        Junk text.
Third:
        Junk text.
Last:
        Copy these lines,
        and replace the text
        in each heading above.
#+END_SRC

** End file
#+BEGIN_SRC 
First:
        Copy these lines,
        and replace the text
        in each heading above.
Second:
        Copy these lines,
        and replace the text
        in each heading above.
Third:
        Copy these lines,
        and replace the text
        in each heading above.
Last:
        Copy these lines,
        and replace the text
        in each heading above.
#+END_SRC

* Reformat/Refactor a Golfer Class

A simple case of removing unneeded code and fixing broken indentation.
** Start file
#+BEGIN_SRC 
class Golfer
     def initialize; end # initialize
  def useless; end;
  
     def self.hello(a,b,c,d)
      puts "Hello #{a}, #{b}, #{c}, #{d}"
   end
end
#+END_SRC

** End file
#+BEGIN_SRC 
class Golfer
  def self.hello(*a)
    puts "Hello #{a.join(',')}"
  end
end
#+END_SRC

* multiple cursor alternative

from: https://www.reddit.com/r/vim/comments/6w5pfa/crosspost_from_remacs_how_would_you_do_this_in_vim/
** Start file
#+BEGIN_SRC 
<section class="top-bar-selection">
  <ul class="left">
    <li class="divider"></li>
    <li class="active">
      <a href="homepage.html">Page 1</a></li>
    <li class="divider"></li>
    <li>
      <a href="homepage.html">Page 2</a></li>
    <li class="divider"></li>
    <li>
      <a href="homepage.html">Page 3</a></li>
    <li class="divider"></li>
    <li>
      <a href="homepage.html">Page 4</a></li>
  </ul>
</section>
#+END_SRC

** End file
#+BEGIN_SRC 
<section class="top-bar-selection">
  <ul class="left">
    <li class="divider"></li>
    <li class="active">
      <a href="Page1.html">Page 1</a></li>
    <li class="divider"></li>
    <li>
      <a href="Page2.html">Page 2</a></li>
    <li class="divider"></li>
    <li>
      <a href="Page3.html">Page 3</a></li>
    <li class="divider"></li>
    <li>
      <a href="Page4.html">Page 4</a></li>
  </ul>
</section>
#+END_SRC

* Split line with dots

This line is too long, split it.
** Start file
#+BEGIN_SRC 
class VimGolf
  def split_me
    MyModel.first_method.second_method(arg).third_method(arg.method_one.method_two)
  end
end
#+END_SRC

** End file
#+BEGIN_SRC 
class VimGolf
  def split_me
    MyModel
      .first_method
      .second_method(arg)
      .third_method(arg.method_one.method_two)
  end
end
#+END_SRC

* switch variable

how fast can you switch two variable ?
** Start file
#+BEGIN_SRC 
int barins, foovariable = 1; 
#+END_SRC

** End file
#+BEGIN_SRC 
int foovariable, barins = 1; 
#+END_SRC

* From argument to object

This task typifies those programmers endure while coding. This C-family pseudocode needs a function argument to be repurposed as an object call. Simply search and replace? Repeat a pattern of edits?
** Start file
#+BEGIN_SRC 
organize(cupboard, 3, 2);
prioritize(bureau, 8, 7);
realize(bannister, 4, 4);
moralize(railing, 3,9);
#+END_SRC

** End file
#+BEGIN_SRC 
cupboard.organize(3, 2);
bureau.prioritize(8, 7);
bannister.realize(4, 4);
railing.moralize(3,9);
#+END_SRC

* -a-b-c-

Put hyphens everywhere.
** Start file
#+BEGIN_SRC 
abcdefghijklm
#+END_SRC

** End file
#+BEGIN_SRC 
-a-b-c-d-e-f-g-h-i-j-k-l-m-
#+END_SRC

* attr_aligner

Two attr keywords. Two separate indentations. Align the colons.
** Start file
#+BEGIN_SRC 
attr_reader :align, :variables, :with
attr_accessor :spaces, :to, :complete, :challenge
# vim: set expandtab:
#+END_SRC

** End file
#+BEGIN_SRC 
attr_reader :align,
            :variables,
            :with
attr_accessor :spaces,
              :to,
              :complete,
              :challenge
# vim: set expandtab:
#+END_SRC

* Triangular Numbers

Generate the first 50 triangular numbers.
** Start file
#+BEGIN_SRC 
0
#+END_SRC

** End file
#+BEGIN_SRC 
0 1 3 6 10 15 21 28 36 45 55 66 78 91 105 120 136 153 171 190 210 231 253 276 300 325 351 378 406 435 465 496 528 561 595 630 666 703 741 780 820 861 903 946 990 1035 1081 1128 1176 1225
#+END_SRC

* Search and Replace 0

Replace every instance of 'aaa' with 'xaaax'.
** Start file
#+BEGIN_SRC 
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
#+END_SRC

** End file
#+BEGIN_SRC 
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
#+END_SRC

* quotes inside quotes

taken from tip 85 of the very good book 'Practical Vim: Edit Text at the Speed of Thought' ! I'd be interested what people use :)
** Start file
#+BEGIN_SRC 
This string contains a 'quoted' word.
This string contains 'two' quoted 'words.'
This 'string doesn't make things easy.'
#+END_SRC

** End file
#+BEGIN_SRC 
This string contains a "quoted" word.
This string contains "two" quoted "words."
This "string doesn't make things easy."
#+END_SRC

* That hyphen

"vim vi improved"
** Start file
#+BEGIN_SRC 
(vim -
vi
improved)
(vim
vi
improved)
#+END_SRC

** End file
#+BEGIN_SRC 
vim vi improved
(vim -
vi
improved)
(vim
vi
improved)
#+END_SRC

* Simple format (2)

try again!
** Start file
#+BEGIN_SRC 
a==b equal to
a!=b not equal to
a>b greater than
a>=b greater than or equal to
a<b less than
a<=b less than or equal to
#+END_SRC

** End file
#+BEGIN_SRC 
        a == b          equal to
        a != b          not equal to
        a >  b          greater than
        a >= b          greater than or equal to
        a <  b          less than
        a <= b          less than or equal to
#+END_SRC

* Extract argument from function

The aim is to see if you can do some refactoring very fast.
** Start file
#+BEGIN_SRC 
attr("y",function(v){return v})
#+END_SRC

** End file
#+BEGIN_SRC 
f=function(v){return v};
attr("y",f)
#+END_SRC

* Preferably without multi-cursor plugin

Originally asked as question on reddit by kpthunder: https://www.reddit.com/r/vim/comments/9fvsro/what_is_the_most_efficient_way_to_go_about/
** Start file
#+BEGIN_SRC 
newState.set('foo', foo);
newState.set('bar', bar);
newState.set('banana', banana);
newState.set('bears', bears);
#+END_SRC

** End file
#+BEGIN_SRC 
state.foo = payload.foo;
state.bar = payload.bar;
state.banana = payload.banana;
state.bears = payload.bears;
#+END_SRC

* Letterbox

Make a box!
** Start file
#+BEGIN_SRC 
abcdefg
#+END_SRC

** End file
#+BEGIN_SRC 
a b c d e f g
b           f
c           e
d           d
e           c
f           b
g f e d c b a
#+END_SRC

* comment and uncomment code inline

It's very useful to be able to comment out a block of code in a quick edit. And likewise to uncomment the code. This operation often involves multi-line stanzas and even large blocks. With just line-wise navigation and insert mode this would cost you about 4 keystrokes per line. Master this hole of VimGolf and you'll quickly drop your key count in day to day Vim as well.
** Start file
#+BEGIN_SRC 
These first three lines should
be commented out with C-style
inline comments.

// These three lines should have
// the C-style insline comment 
// characters removed.
#+END_SRC

** End file
#+BEGIN_SRC 
// These first three lines should
// be commented out with C-style
// inline comments.

These three lines should have
the C-style insline comment 
characters removed.
#+END_SRC

* Adam's challenge

Change both normal to bold and 4 by 2. Adam Wathan challenge this on twitter . He did it in 11 keystrokes on Sublime.
** Start file
#+BEGIN_SRC 
<div>
    <span class="text-base text-dark wt-normal">
        @icon('line-graph', 'icon-sm text-dark-faint m-r-4') ${{ number_format($product->totalRevenue() / 100) }}
    </span>
    <span class="text-base text-dark wt-normal">
        @icon('users', 'icon-sm text-dark-faint m-r-4') {{ $product->totalPurchases() }}
    </span>
</div>
#+END_SRC

** End file
#+BEGIN_SRC 
<div>
    <span class="text-base text-dark wt-bold">
        @icon('line-graph', 'icon-sm text-dark-faint m-r-2') ${{ number_format($product->totalRevenue() / 100) }}
    </span>
    <span class="text-base text-dark wt-bold">
        @icon('users', 'icon-sm text-dark-faint m-r-2') {{ $product->totalPurchases() }}
    </span>
</div>
#+END_SRC

* Flip the bit

Change the specific 0 to a 1.
** Start file
#+BEGIN_SRC 
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
#+END_SRC

** End file
#+BEGIN_SRC 
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000001000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
00000000000000000000000000000000
#+END_SRC

* Missing Library and a Typo

I forgot to add a c library, please add it for me. Also I'm bad at typing so fix my typo too.
** Start file
#+BEGIN_SRC 
#define MIN_NUMBER 1
#define MAX_NUMBER 100
#include <stdio.h>
#include <time.h>
#include <stdlib.h>

int getGuess(){
    int c;
    int guess = 0;

    while(guess < MIN_NUMBER || guess > MAX_NUMBER){
        printf("Guess: ");
        scanf("%d", &guess);

        while((c = getchar()) != '\n' && c != EOF);
    }

    return guess;
}

int main(){
    srand(time(NULL));
    int number = rand()%(MAX_NUMBER-MIN_NUMBER+1)+MIN_NUMBER;

    printf("Let's start a game.\n");
    printf("I've picked a number between %d and %d\n",MIN_NUMBER,MAX_NUMBER);
    printf("Guess what it is and I'll tell you \n");
    printf("if it's higher or lower.\n");
    printf("You win if you guess it in 7 turns or less\n\n");

    int turn;
    for(turn = 0; turn < 7; turn++){
        int guess = getGuess();
        assert(guess>=MIN_NUMBER && guess<=MAX_NUMBER);

        if(guess < number){
            printf("Higher\n\n");
        }else if(guess > number){
            printf("Lower\n\n");
        }else{
            break;
        }
    }

    if(turn < 7)
        printf("\nYou Win!\n");
    else
        printf("You Lose the answer was %d.\n", number);

    return 0;
}
// I think I forgot to include the library assetr
#+END_SRC

** End file
#+BEGIN_SRC 
#define MIN_NUMBER 1
#define MAX_NUMBER 100
#include <stdio.h>
#include <time.h>
#include <stdlib.h>
#include <assert.h>

int getGuess(){
    int c;
    int guess = 0;

    while(guess < MIN_NUMBER || guess > MAX_NUMBER){
        printf("Guess: ");
        scanf("%d", &guess);

        while((c = getchar()) != '\n' && c != EOF);
    }

    return guess;
}

int main(){
    srand(time(NULL));
    int number = rand()%(MAX_NUMBER-MIN_NUMBER+1)+MIN_NUMBER;

    printf("Let's start a game.\n");
    printf("I've picked a number between %d and %d\n",MIN_NUMBER,MAX_NUMBER);
    printf("Guess what it is and I'll tell you \n");
    printf("if it's higher or lower.\n");
    printf("You win if you guess it in 7 turns or less\n\n");

    int turn;
    for(turn = 0; turn < 7; turn++){
        int guess = getGuess();
        assert(guess>=MIN_NUMBER && guess<=MAX_NUMBER);

        if(guess < number){
            printf("Higher\n\n");
        }else if(guess > number){
            printf("Lower\n\n");
        }else{
            break;
        }
    }

    if(turn < 7)
        printf("\nYou Win!\n");
    else
        printf("You Lose the answer was %d.\n", number);

    return 0;
}
// I think I forgot to include the library assert
#+END_SRC

* Don't know what this is

Replace contents of brackets with matching number of spaces. Don't ask what the format's supposed to be.
** Start file
#+BEGIN_SRC 
[1:0]
[0:1]
[1:100]
[0:100]
#+END_SRC

** End file
#+BEGIN_SRC 
[   ]
[   ]
[     ]
[     ]
#+END_SRC

* Real World PHP To Markdown

Fun refactoring I had to do in the real world. This presents several challenges: - How to create a table that fits the informations exactly - How to keep track of two informations per line while doing the refactoring - Generate the link from the actual text Have fun!
** Start file
#+BEGIN_SRC 
    public const SCHEMA_MAPPED_CONSTRAINTS = [
        Url::class => 'http://schema.org/url',
        Email::class => 'http://schema.org/email',
        Uuid::class => 'http://schema.org/identifier',
        CardScheme::class => 'http://schema.org/identifier',
        Bic::class => 'http://schema.org/identifier',
        Iban::class => 'http://schema.org/identifier',
        Date::class => 'http://schema.org/Date',
        DateTime::class => 'http://schema.org/DateTime',
        Time::class => 'http://schema.org/Time',
        Image::class => 'http://schema.org/image',
        File::class => 'http://schema.org/MediaObject',
        Currency::class => 'http://schema.org/priceCurrency',
        Isbn::class => 'http://schema.org/isbn',
        Issn::class => 'http://schema.org/issn',
    ];
#+END_SRC

** End file
#+BEGIN_SRC 
Constraints                                                                           | Vocabulary                        |
--------------------------------------------------------------------------------------|-----------------------------------|
[`Url`](https://symfony.com/doc/current/reference/constraints/Url.html)               | `http://schema.org/url`           |
[`Email`](https://symfony.com/doc/current/reference/constraints/Email.html)           | `http://schema.org/email`         |
[`Uuid`](https://symfony.com/doc/current/reference/constraints/Uuid.html)             | `http://schema.org/identifier`    |
[`CardScheme`](https://symfony.com/doc/current/reference/constraints/CardScheme.html) | `http://schema.org/identifier`    |
[`Bic`](https://symfony.com/doc/current/reference/constraints/Bic.html)               | `http://schema.org/identifier`    |
[`Iban`](https://symfony.com/doc/current/reference/constraints/Iban.html)             | `http://schema.org/identifier`    |
[`Date`](https://symfony.com/doc/current/reference/constraints/Date.html)             | `http://schema.org/Date`          |
[`DateTime`](https://symfony.com/doc/current/reference/constraints/DateTime.html)     | `http://schema.org/DateTime`      |
[`Time`](https://symfony.com/doc/current/reference/constraints/Time.html)             | `http://schema.org/Time`          |
[`Image`](https://symfony.com/doc/current/reference/constraints/Image.html)           | `http://schema.org/image`         |
[`File`](https://symfony.com/doc/current/reference/constraints/File.html)             | `http://schema.org/MediaObject`   |
[`Currency`](https://symfony.com/doc/current/reference/constraints/Currency.html)     | `http://schema.org/priceCurrency` |
[`Isbn`](https://symfony.com/doc/current/reference/constraints/Isbn.html)             | `http://schema.org/isbn`          |
[`Issn`](https://symfony.com/doc/current/reference/constraints/Issn.html)             | `http://schema.org/issn`          |
#+END_SRC

* Learn some german verbs

The list needs to be structured so we can print in verbatim and feel ok about how it looks.
** Start file
#+BEGIN_SRC 
1. sein to be
2. haben to have
3. werden to become
4. können can, to be able to
5. müssen must, to have to
6. sagen to say
7. machen to do, make
8. geben to give
9. kommen to come
10. bestehen to exist, insist, pass (an exam)
#+END_SRC

** End file
#+BEGIN_SRC 
sein     - to be
haben    - to have
werden   - to become
können   - can, to be able to
müssen   - must, to have to
sagen    - to say
machen   - to do, make
geben    - to give
kommen   - to come
bestehen - to exist, insist, pass (an exam)
#+END_SRC

* replacing each line of a block selection

replace each line's ../assets/js with /javascripts
** Start file
#+BEGIN_SRC 
<script src="../assets/js/jquery.js"></script>
<script src="../assets/js/bootstrap-transition.js"></script>
<script src="../assets/js/bootstrap-alert.js"></script>
<script src="../assets/js/bootstrap-modal.js"></script>
<script src="../assets/js/bootstrap-dropdown.js"></script>

<script src="../assets/js/bootstrap-scrollspy.js"></script>
<script src="../assets/js/bootstrap-tab.js"></script>
<script src="../assets/js/bootstrap-tooltip.js"></script>
<script src="../assets/js/bootstrap-popover.js"></script>
<script src="../assets/js/bootstrap-button.js"></script>
<script src="../assets/js/bootstrap-collapse.js"></script>

<script src="../assets/js/bootstrap-carousel.js"></script>
<script src="../assets/js/bootstrap-typeahead.js"></script>
#+END_SRC

** End file
#+BEGIN_SRC 
<script src="/javascripts/jquery.js"></script>
<script src="/javascripts/bootstrap-transition.js"></script>
<script src="/javascripts/bootstrap-alert.js"></script>
<script src="/javascripts/bootstrap-modal.js"></script>
<script src="/javascripts/bootstrap-dropdown.js"></script>

<script src="/javascripts/bootstrap-scrollspy.js"></script>
<script src="/javascripts/bootstrap-tab.js"></script>
<script src="/javascripts/bootstrap-tooltip.js"></script>
<script src="/javascripts/bootstrap-popover.js"></script>
<script src="/javascripts/bootstrap-button.js"></script>
<script src="/javascripts/bootstrap-collapse.js"></script>

<script src="/javascripts/bootstrap-carousel.js"></script>
<script src="/javascripts/bootstrap-typeahead.js"></script>
#+END_SRC

* Fiddle percentages into real numbers

Get rid of the '%' symbols and shift the decimal place. This is the easier version - all the columns line up.
** Start file
#+BEGIN_SRC 
1,25.1%,good
2,19.8%,bad
3,30.5%,bad
4,71.4%,good
5,16.8%,bad
6,93.9%,good
8,37.1%,bad
9,35.3%,bad
#+END_SRC

** End file
#+BEGIN_SRC 
1,.251,good
2,.198,bad
3,.305,bad
4,.714,good
5,.168,bad
6,.939,good
8,.371,bad
9,.353,bad
#+END_SRC

* Space out the alphabet

Put 3 spaces between adjacent letters.
** Start file
#+BEGIN_SRC 
abcde
fghij
klmno
pqrst
uvwxyz
#+END_SRC

** End file
#+BEGIN_SRC 
a   b   c   d   e
f   g   h   i   j
k   l   m   n   o
p   q   r   s   t
u   v   w   x   y   z
#+END_SRC

* There is no vertical limit for vim Ninjas

** Start file

#+BEGIN_SRC 
 There
 is
 no
 vertical
 limit
 for
 vim
 Ninjas
#+END_SRC

** End file
#+BEGIN_SRC 
[ "There", "is", "no", "vertical", "limit", "for", "vim", "Ninjas" ]
#+END_SRC
* Whitespace, empty lines and tabs

Convert tabs to spaces, strip empty lines and trailing whitespace.
** Start file
#+BEGIN_SRC 
	convert tabs to spaces

		strip all blank lines 

	and remove any trailing spaces	 
#+END_SRC

** End file
#+BEGIN_SRC 
  convert tabs to spaces
    strip all blank lines
  and remove any trailing spaces
#+END_SRC

* Order and join

There's something special about the input order.
** Start file
#+BEGIN_SRC 
four
one
two
five
three
six
#+END_SRC

** End file
#+BEGIN_SRC 
one two three
four five
six
#+END_SRC

* Kolakoski sequence -- level 1

Generate the Kolakoski sequence as described by its first 75 terms.
** Start file
#+BEGIN_SRC 
122
#+END_SRC

** End file
#+BEGIN_SRC 
12211212212211211221211212211211212212211212212112112212211212212211211212212112212211212212211211221211212212211
#+END_SRC

* Swap the operands under comparison

Swap the operands under comparison to prevent null pointer exception (at least in java)
** Start file
#+BEGIN_SRC 
if(lang.equals("en_US")) {
        System.out.println("The lang is en_US i.e english US"+
}

if(lang.equals("es_US")) {
        System.out.println("The lang is es_US i.e spanish US"+
}

if(lang.equals("fr_US")) {
        System.out.println("The lang is fr_US i.e france US"+
}
#+END_SRC

** End file
#+BEGIN_SRC 
if("en_US".equals(lang)) {
        System.out.println("The lang is en_US i.e english US"+
}

if("es_US".equals(lang)) {
        System.out.println("The lang is es_US i.e spanish US"+
}

if("fr_US".equals(lang)) {
        System.out.println("The lang is fr_US i.e france US"+
}
#+END_SRC

* Saving the hashes(#)

The following file is copied from vimcasts.org(Its only for learning purpose,hope the site owner doesn't mind it), its probably the easiest of challenges.Our goal is to delete every line which doesn't contain a hash signs. The remaining hash signs with numbers are then sorted to get the final output.
** Start file
#+BEGIN_SRC 
January 2013
#40 Long-range line duplication (6:31)
December 2012
#39 Profiling Vimscript performance (8:09)
November 2012
#38 Writing a custom fold expression (12:07) #37 How to fold (8:49)
August 2012
#36 VimGolf - Prime Numbers (6:53)
May 2011
#35 Fugitive.vim - exploring the history of a git repository (10:04) #34 Fugitive.vim - browsing the git object database (9:45) #33 Fugitive.vim - resolving merge conflicts with vimdiff (11:35)
April 2011
#32 Fugitive.vim - working with the git index (11:41) #31 Fugitive.vim - a complement to command line git (8:27)
February 2011
#30 Undo branching and Gundo.vim (6:30)
January 2011
#29 Aligning text with Tabular.vim (5:11)
November 2010
#28 Refining search patterns with the command-line window (7:51)
October 2010
#27 Synchronizing plugins with git submodules and pathogen (9:24) #26 Bubbling text (6:23)
September 2010
#25 Creating colorschemes for Vim (9:44)
July 2010
#24 Updating your vimrc file on the fly (2:51) #23 Converting HAML to ERB with Vim macros (7:36)
June 2010
#22 Selecting columns with visual block mode (4:21) #21 Converting markdown to structured HTML with a macro (9:25)
May 2010
#20 Running Vim within IRB (4:35) #19 Spell checking (5:42) #18 Formatting text with par (5:12)
April 2010
#17 Hard wrapping text (5:23) #16 Soft wrapping text (4:54) #15 The file explorer (5:36) #14 The :edit command (3:50) #13 Cleaning up with Vim (0:36)
March 2010
#12 Modal editing: undo, redo and repeat (5:26) #11 Using the changelist and jumplist (3:21) #10 Creating the Vimcasts logo as ASCII art (5:47) #9 How to use tabs (5:28)
February 2010
#8 Working with tabs (3:17) #7 Working with windows (5:32) #6 Working with buffers (3:28) #5 Indentation commands (5:41)
January 2010
#4 Tidying whitespace (4:33) #3 Whitespace preferences and filetypes (3:29) #2 Tabs and Spaces (6:22) #1 Show invisibles (2:52) 
#+END_SRC

** End file
#+BEGIN_SRC 
#1 Show invisibles (2:52) 
#2 Tabs and Spaces (6:22)
#3 Whitespace preferences and filetypes (3:29)
#4 Tidying whitespace (4:33)
#5 Indentation commands (5:41)
#6 Working with buffers (3:28)
#7 Working with windows (5:32)
#8 Working with tabs (3:17)
#9 How to use tabs (5:28)
#10 Creating the Vimcasts logo as ASCII art (5:47)
#11 Using the changelist and jumplist (3:21)
#12 Modal editing: undo, redo and repeat (5:26)
#13 Cleaning up with Vim (0:36)
#14 The :edit command (3:50)
#15 The file explorer (5:36)
#16 Soft wrapping text (4:54)
#17 Hard wrapping text (5:23)
#18 Formatting text with par (5:12)
#19 Spell checking (5:42)
#20 Running Vim within IRB (4:35)
#21 Converting markdown to structured HTML with a macro (9:25)
#22 Selecting columns with visual block mode (4:21)
#23 Converting HAML to ERB with Vim macros (7:36)
#24 Updating your vimrc file on the fly (2:51)
#25 Creating colorschemes for Vim (9:44)
#26 Bubbling text (6:23)
#27 Synchronizing plugins with git submodules and pathogen (9:24)
#28 Refining search patterns with the command-line window (7:51)
#29 Aligning text with Tabular.vim (5:11)
#30 Undo branching and Gundo.vim (6:30)
#31 Fugitive.vim - a complement to command line git (8:27)
#32 Fugitive.vim - working with the git index (11:41)
#33 Fugitive.vim - resolving merge conflicts with vimdiff (11:35)
#34 Fugitive.vim - browsing the git object database (9:45)
#35 Fugitive.vim - exploring the history of a git repository (10:04)
#36 VimGolf - Prime Numbers (6:53)
#37 How to fold (8:49)
#38 Writing a custom fold expression (12:07)
#39 Profiling Vimscript performance (8:09)
#40 Long-range line duplication (6:31)
#+END_SRC

* unknown command

I want change 5 words
** Start file
#+BEGIN_SRC 
I like simplicity : Nneba Fjnegm naq Wbua Tehore
#+END_SRC

** End file
#+BEGIN_SRC 
I like simplicity : Aaron Swartz and John Gruber
#+END_SRC

* Align commas

There are 15,000 aligning challenges on vimgolf.com, and they're all exactly the same. I hope this one is a little different.
** Start file
#+BEGIN_SRC 
just = make,
       all,
       the,
       commas,
       line,
       up
#+END_SRC

** End file
#+BEGIN_SRC 
just = make  ,
       all   ,
       the   ,
       commas,
       line  ,
       up
#+END_SRC

* comments galore

Basic comment reformatting
** Start file
#+BEGIN_SRC 
/*
 * comments
 * yay comments
 * so informative, the information is really yes
 * wowowowowow
 * mind blown
 * and that's how the allocator works
 */
#+END_SRC

** End file
#+BEGIN_SRC 
// comments
// yay comments
// so informative, the information is really yes
// wowowowowow
// mind blown
// and that's how the allocator works
#+END_SRC

* Switch function arguments

How to switch two arguments of a function.
** Start file
#+BEGIN_SRC 
function testFunction (foo, bar) {
}
#+END_SRC

** End file
#+BEGIN_SRC 
function testFunction (bar, foo) {
}
#+END_SRC

* Pascal's Triangle

Generate the first 17 left-justified rows of Pascal's triangle.
** Start file
#+BEGIN_SRC 
0
#+END_SRC

** End file
#+BEGIN_SRC 
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
1 5 10 10 5 1
1 6 15 20 15 6 1
1 7 21 35 35 21 7 1
1 8 28 56 70 56 28 8 1
1 9 36 84 126 126 84 36 9 1
1 10 45 120 210 252 210 120 45 10 1
1 11 55 165 330 462 462 330 165 55 11 1
1 12 66 220 495 792 924 792 495 220 66 12 1
1 13 78 286 715 1287 1716 1716 1287 715 286 78 13 1
1 14 91 364 1001 2002 3003 3432 3003 2002 1001 364 91 14 1
1 15 105 455 1365 3003 5005 6435 6435 5005 3003 1365 455 105 15 1
1 16 120 560 1820 4368 8008 11440 12870 11440 8008 4368 1820 560 120 16 1
#+END_SRC

* Number Sort

sort the list of newline-separated numbers incrementally. Numbers are in the range 1 to 1000, with 500 missing
** Start file
#+BEGIN_SRC 
960
90
196
650
219
422
513
184
146
885
695
409
974
415
307
784
43
477
140
651
137
648
119
906
228
473
940
408
931
99
661
426
540
832
575
996
970
385
243
147
888
915
521
482
451
702
667
697
478
368
987
636
921
829
681
46
766
598
999
132
626
726
245
312
199
902
420
715
835
811
145
959
221
734
514
520
645
357
838
950
993
899
430
338
327
26
124
374
135
817
403
101
47
882
933
339
192
666
946
793
692
688
605
529
4
323
789
468
396
912
606
449
31
308
421
799
656
769
844
131
743
920
783
432
320
948
790
595
512
696
872
689
916
621
231
208
633
445
57
412
945
627
263
325
217
56
345
805
895
340
590
429
324
187
23
34
413
617
919
732
549
772
5
377
683
485
973
329
313
126
552
924
855
559
175
207
742
771
991
763
883
69
988
729
824
876
48
898
580
222
180
718
524
366
501
721
630
462
812
443
130
62
332
561
568
1
66
490
386
995
884
152
298
10
441
934
239
800
813
543
935
300
53
44
659
170
951
922
3
186
591
544
2
96
706
218
775
395
211
622
162
516
930
257
947
607
896
740
64
68
317
51
655
997
963
424
197
13
400
352
745
968
434
551
92
122
866
203
976
587
405
699
52
642
803
109
592
760
54
647
828
168
354
953
251
476
843
757
929
565
247
448
250
534
733
11
191
755
823
148
754
809
577
518
539
190
765
276
955
294
541
253
701
475
206
375
557
615
113
25
853
779
499
216
493
30
142
725
808
279
65
749
600
949
80
82
97
288
394
24
674
398
28
640
365
854
664
159
411
399
1000
193
427
758
459
333
849
525
350
901
641
553
201
936
542
16
428
178
45
141
810
165
652
455
185
830
746
687
925
123
433
306
444
503
389
37
635
183
747
452
794
41
868
376
804
486
234
818
722
481
890
748
238
778
711
719
984
438
550
85
282
291
19
634
983
467
566
603
287
311
87
235
676
807
129
738
295
344
998
161
75
360
535
336
911
156
209
150
875
880
315
281
584
379
414
480
833
927
507
367
9
582
233
94
67
261
509
684
278
848
285
918
404
232
127
275
93
562
177
560
293
172
943
774
678
586
827
837
343
764
418
84
939
679
176
447
662
588
391
952
781
822
962
894
523
616
992
483
83
785
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
3
4
5
9
10
11
13
16
19
23
24
25
26
28
30
31
34
37
41
43
44
45
46
47
48
51
52
53
54
56
57
62
64
65
66
67
68
69
75
80
82
83
84
85
87
90
92
93
94
96
97
99
101
109
113
119
122
123
124
126
127
129
130
131
132
135
137
140
141
142
145
146
147
148
150
152
156
159
161
162
165
168
170
172
175
176
177
178
180
183
184
185
186
187
190
191
192
193
196
197
199
201
203
206
207
208
209
211
216
217
218
219
221
222
228
231
232
233
234
235
238
239
243
245
247
250
251
253
257
261
263
275
276
278
279
281
282
285
287
288
291
293
294
295
298
300
306
307
308
311
312
313
315
317
320
323
324
325
327
329
332
333
336
338
339
340
343
344
345
350
352
354
357
360
365
366
367
368
374
375
376
377
379
385
386
389
391
394
395
396
398
399
400
403
404
405
408
409
411
412
413
414
415
418
420
421
422
424
426
427
428
429
430
432
433
434
438
441
443
444
445
447
448
449
451
452
455
459
462
467
468
473
475
476
477
478
480
481
482
483
485
486
490
493
499
501
503
507
509
512
513
514
516
518
520
521
523
524
525
529
534
535
539
540
541
542
543
544
549
550
551
552
553
557
559
560
561
562
565
566
568
575
577
580
582
584
586
587
588
590
591
592
595
598
600
603
605
606
607
615
616
617
621
622
626
627
630
633
634
635
636
640
641
642
645
647
648
650
651
652
655
656
659
661
662
664
666
667
674
676
678
679
681
683
684
687
688
689
692
695
696
697
699
701
702
706
711
715
718
719
721
722
725
726
729
732
733
734
738
740
742
743
745
746
747
748
749
754
755
757
758
760
763
764
765
766
769
771
772
774
775
778
779
781
783
784
785
789
790
793
794
799
800
803
804
805
807
808
809
810
811
812
813
817
818
822
823
824
827
828
829
830
832
833
835
837
838
843
844
848
849
853
854
855
866
868
872
875
876
880
882
883
884
885
888
890
894
895
896
898
899
901
902
906
911
912
915
916
918
919
920
921
922
924
925
927
929
930
931
933
934
935
936
939
940
943
945
946
947
948
949
950
951
952
953
955
959
960
962
963
968
970
973
974
976
983
984
987
988
991
992
993
995
996
997
998
999
1000
#+END_SRC

* Letter case trickery

This file is in a downright esoteric format, consisting of hexadecimal numbers, non-hexadecimal keywords, and "Z" indicating end-of-line. Make the hexadecimal numbers lowercase.
** Start file
#+BEGIN_SRC 
A4E SUM 3C0Z
2B A9 NE F2Z
#+END_SRC

** End file
#+BEGIN_SRC 
a4e SUM 3c0Z
2b a9 NE f2Z
#+END_SRC

* Python challenge

Change the types of the variables in the list from str to float, while keeping the truncation.
** Start file
#+BEGIN_SRC 
a = ['%.3f' % 3.5313423, '%.1f' % 35.66]
b = ['%.3f' % 3.90022, '%.1f' % 95.501033]
c = ['%.5f' % self.numbers[2]]
#+END_SRC

** End file
#+BEGIN_SRC 
a = [round(3.5313423, 3), round(35.66, 1)]
b = [round(3.90022, 3), round(95.501033, 1)]
c = [round(self.numbers[2], 5)]
#+END_SRC

* Make it more readable

Insert blank lines to make it more organized and readable
** Start file
#+BEGIN_SRC 
#Set the global prefix key to C-q (default is C-b)
set-option -g prefix C-q
bind-key C-q last-window
# Remove default binding since we’re replacing
unbind %
bind | split-window -h
bind - split-window -v
# Set status bar
set -g status-bg black
set -g status-fg white
set -g status-left '#[fg=green]#H'
# Highlight active window
set-window-option -g window-status-current-bg red
set -g status-right '#[fg=yellow]#(uptime | cut -d "," -f 2-)'
# Set window notifications
setw -g monitor-activity on
set -g visual-activity on
# Automatically set window title
setw -g automatic-rename
#+END_SRC

** End file
#+BEGIN_SRC 
#Set the global prefix key to C-q (default is C-b)
set-option -g prefix C-q
bind-key C-q last-window


# Remove default binding since we’re replacing
unbind %
bind | split-window -h
bind - split-window -v


# Set status bar
set -g status-bg black
set -g status-fg white
set -g status-left '#[fg=green]#H'


# Highlight active window
set-window-option -g window-status-current-bg red
set -g status-right '#[fg=yellow]#(uptime | cut -d "," -f 2-)'


# Set window notifications
setw -g monitor-activity on
set -g visual-activity on


# Automatically set window title
setw -g automatic-rename
#+END_SRC

* Scrambled numbers

Four is NOT 1. One is 1.
** Start file
#+BEGIN_SRC 
Four is 1.
One is 2.
Five is 3.
Three is 4.
Six is 5.
Two is 6.
#+END_SRC

** End file
#+BEGIN_SRC 
One is 1.
Two is 2.
Three is 3.
Four is 4.
Five is 5.
Six is 6.
#+END_SRC

* Make HTML List

Turn the comma separated list into an unordered html list.
** Start file
#+BEGIN_SRC 
item1,item2,item3,item4,item5
#+END_SRC

** End file
#+BEGIN_SRC 
<ul>
        <li>item1</li>
        <li>item2</li>
        <li>item3</li>
        <li>item4</li>
        <li>item5</li>
</ul>
#+END_SRC

* C Reformatting

You may use Visual mode... or not. #uppercase
** Start file
#+BEGIN_SRC 
typedef enum {
   FORMAT_AUDIO_UNKNOWN = 0,
   FORMAT_AUDIO_VORBIS  = 1,
   FORMAT_AUDIO_PCM_U8  = 2,
   FORMAT_AUDIO_PCM_S16LE = 3,
   FORMAT_AUDIO_PCM_S24LE = 4,
   FORMAT_AUDIO_ADPCM_MS = 5, /*!< Microsoft ADPCM */
   FORMAT_AUDIO_AAC = 6,      /*!< Detected but not supported */
   FORMAT_AUDIO_OPUS = 7,     /*!< Xiph Opus */
   FORMAT_AUDIO_NONE = 0x10
} FMT_audio_type;
/* --- */
#+END_SRC

** End file
#+BEGIN_SRC 
FMT_AUDIO_TYPE(FORMAT_AUDIO_UNKNOWN, 0);
FMT_AUDIO_TYPE(FORMAT_AUDIO_VORBIS, 1);
FMT_AUDIO_TYPE(FORMAT_AUDIO_PCM_U8, 2);
FMT_AUDIO_TYPE(FORMAT_AUDIO_PCM_S16LE, 3);
FMT_AUDIO_TYPE(FORMAT_AUDIO_PCM_S24LE, 4);
FMT_AUDIO_TYPE(FORMAT_AUDIO_ADPCM_MS, 5);
FMT_AUDIO_TYPE(FORMAT_AUDIO_AAC, 6);
FMT_AUDIO_TYPE(FORMAT_AUDIO_OPUS, 7);
FMT_AUDIO_TYPE(FORMAT_AUDIO_NONE, 0x10);
#+END_SRC

* Numbering a List

Pretty simple, number the list.
** Start file
#+BEGIN_SRC 
line one
line two
line three
line four
line five
line six
line seven
line eight
#+END_SRC

** End file
#+BEGIN_SRC 
1. line one
2. line two
3. line three
4. line four
5. line five
6. line six
7. line seven
8. line eight
#+END_SRC

* Do you demand a shrubbery?

Use :redir and crush the emacsgolfers.
** Start file
#+BEGIN_SRC 
:Ni!
#+END_SRC

** End file
#+BEGIN_SRC 
:Ni!


Do you demand a shrubbery?
#+END_SRC

* Fix the XML

The challenge consists in having a valid xml from an incomplete source.
** Start file
#+BEGIN_SRC 
<I>
    <hate>
        <xml>hello
        <files>files
    </hate>
    <hate>
        <xml>xml
        <files>world
    </hate>
</I>
#+END_SRC

** End file
#+BEGIN_SRC 
<I>
    <hate>
        <xml>hello</xml>
        <files>files</files>
    </hate>
    <hate>
        <xml>xml</xml>
        <files>world</files>
    </hate>
</I>
#+END_SRC

* Array Transposition

Transpose four arrays into two.
** Start file
#+BEGIN_SRC 
[v,m,o,f]
[i,g,l]
[i,b,n,f,c,a]
[s,e,e,i,a,l]
#+END_SRC

** End file
#+BEGIN_SRC 
[v,i,m,g,o,l,f]
[i,s,b,e,n,e,f,i,c,i,a,l]
#+END_SRC

* SFD-ROC: vimvimvim

Oh no, this line is longer than 80 chars... put each 'vim' on a new line.
** Start file
#+BEGIN_SRC 
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
#+END_SRC

** End file
#+BEGIN_SRC 
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
vim
#+END_SRC

* Shebangs for all

We've all seen or used a shebang once or twice. Ditch the specific paths and leave just a dynamic Ruby and Python bath behind.
** Start file
#+BEGIN_SRC 
#!/usr/bin/ruby

#!/usr/bin/env ruby

#!/usr/local/bin/python

#!/usr/python
#+END_SRC

** End file
#+BEGIN_SRC 
#!/usr/bin/env ruby

#!/usr/bin/env python
#+END_SRC

* Count both ways

Right AND down.
** Start file
#+BEGIN_SRC 
one two three four five six seven eight nine ten eleven
#+END_SRC

** End file
#+BEGIN_SRC 
one two three four five six seven eight nine ten eleven
two
three
four
five
six
seven
eight
nine
ten
eleven
#+END_SRC

* Mess in revision history

Help Joe clean up what Steve has cobbled.
** Start file
#+BEGIN_SRC 
date         rel  who      what
2010-02-01   1.0  joe      initial version
2011-Feb-1 1.2 steve fixed some typos
2011-10-14 1.2 joe   copyrights updated
2014-01-09 2.0 joe   framework upgraded
#+END_SRC

** End file
#+BEGIN_SRC 
date         rel  who      what
2010-02-01   1.0  joe      initial version
2011-02-01   1.2  steve    fixed some typos
2011-10-14   1.2  joe      copyrights updated
2014-01-09   2.0  joe      framework upgraded
#+END_SRC

* Mirror Symmetry

Add backslashes.
** Start file
#+BEGIN_SRC 
|/-/-/-/|
#+END_SRC

** End file
#+BEGIN_SRC 
|\/-\/-\/-\/|
#+END_SRC

* The D a n k Side of the Moon

You're making a vaporwave cover of The Dark Side of the Moon. So for the tracklisting, you want to: 1. Change the track names to v a p o r c a s e 2. Double the track lengths (since you're slowing them down). Well... let's just double the minutes.
** Start file
#+BEGIN_SRC 
The Dark Side of the Moon

1. Speak to Me (1:13)
2. Breathe (2:41)
3. On the Run (3:30)
4. Time (6:52)
5. The Great Gig in the Sky (4:16)
6. Money (6:23)
7. Us and Them (7:49)
8. Any Colour You Like (3:25)
9. Brain Damage (3:49)
10. Eclipse (2:03)
#+END_SRC

** End file
#+BEGIN_SRC 
The  D a n k  Side of the Moon

1.  S p e a k   t o   M e  (2:13)
2.  B r e a t h e  (4:41)
3.  O n   t h e   R u n  (6:30)
4.  T i m e  (12:52)
5.  T h e   G r e a t   G i g   i n   t h e   S k y  (8:16)
6.  M o n e y  (12:23)
7.  U s   a n d   T h e m  (14:49)
8.  A n y   C o l o u r   Y o u   L i k e  (6:25)
9.  B r a i n   D a m a g e  (6:49)
10.  E c l i p s e  (4:03)
#+END_SRC

* camel riding

add a prefix on some camelCase variables
** Start file
#+BEGIN_SRC 
val (schemas, activeCount, techTagCount, sharedCount, allowedPathsCount, rootCount, searchableCount) = fieldStats(store)
#+END_SRC

** End file
#+BEGIN_SRC 
val (schemas, schActiveCount, schTechTagCount, schSharedCount, schAllowedPathsCount, schRootCount, schSearchableCount) = fieldStats(store)
#+END_SRC

* Array propagate

Complete the array with the keys as part of the value
** Start file
#+BEGIN_SRC 
$arr = [
    'one_option' => '',
    'other' => '',
    'created_at' => '',
    'updated_at' => ''
]
#+END_SRC

** End file
#+BEGIN_SRC 
$arr = [
    'one_option' => $row['one_option'],
    'other' => $row['other'],
    'created_at' => $row['created_at'],
    'updated_at' => $row['updated_at']
]
#+END_SRC

* Where should I put the Newline?

Help me put the newline.
** Start file
#+BEGIN_SRC 
You see this --->newline<--- that is the newline.
#+END_SRC

** End file
#+BEGIN_SRC 
You see this --->
<--- that is the newline.
#+END_SRC

* Hole-in-one

Lets take this golf thing literally.. Drive off the tee into the hole, and of course you don't strike the ball completely clean.
** Start file
#+BEGIN_SRC 
    
        o
        |


                                     |>
                                     |
                                    ( )
#+END_SRC

** End file
#+BEGIN_SRC 
    
        
        
          _

                                     |>
                                     |
                                    (o)
#+END_SRC

* From A to B

Mirror and change this text block
** Start file
#+BEGIN_SRC 
A.a.A.A.A
A.A.a.A.A
A.A.A.a.A
#+END_SRC

** End file
#+BEGIN_SRC 
BBBbB
BBbBB
BbBBB
#+END_SRC

* remove dupes from array

given a random string that contains a ruby-esque array, make sure that there are no duplicate elements
** Start file
#+BEGIN_SRC 
[11, 2, 3,5  , 1,1, 22, 4]
#+END_SRC

** End file
#+BEGIN_SRC 
[1, 2, 3, 4, 5, 11, 22]
#+END_SRC

* Todo list specification

The every item on the todo list must be done today. Modify the list to reflect that.
** Start file
#+BEGIN_SRC 
#87 do the laundry
#25 take out the trash
#97 wash the dishes
#19 mow the lawn
#48 walk the dog
#89 water the plants
#11 pick up the living room
#64 clean the bathroom
#58 dust the shelves
#+END_SRC

** End file
#+BEGIN_SRC 
#87 do the laundry
 87 needs to be done today
#25 take out the trash
 25 needs to be done today
#97 wash the dishes
 97 needs to be done today
#19 mow the lawn
 19 needs to be done today
#48 walk the dog
 48 needs to be done today
#89 water the plants
 89 needs to be done today
#11 pick up the living room
 11 needs to be done today
#64 clean the bathroom
 64 needs to be done today
#58 dust the shelves
 58 needs to be done today
#+END_SRC

* Santa's naughty / nice list

Christmas is here and Santa hasn't decided who's naughty or nice yet. He's given a list of names to his programmer friend to quickly split the children into naughty and nice. Hint: There's a hidden pattern that might be familiar.
** Start file
#+BEGIN_SRC 
Ayden
Jayden
Linnett
Sam
Zooey
Wyn
Winter
Wynne
Madelyn
Michael
Jessica
Thomas
Olivia
Maria
Julia
Aaron
Iris
Adrian
Nathaniel
Alice
Margaret
Miranda
Oliver
Philip
Phoebe
Marcus
Arthur
Tatiana
Robin
Ophelia
#+END_SRC

** End file
#+BEGIN_SRC 
nice Ayden
nice Jayden
naughty Linnett
nice Sam
naughty Zooey
naughty Wyn
nice Winter
nice Wynne
naughty Madelyn
naughty Michael
nice Jessica
naughty Thomas
nice Olivia
nice Maria
naughty Julia
nice Aaron
nice Iris
naughty Adrian
nice Nathaniel
naughty Alice
naughty Margaret
nice Miranda
nice Oliver
naughty Philip
naughty Phoebe
nice Marcus
naughty Arthur
nice Tatiana
nice Robin
naughty Ophelia
#+END_SRC

* Condensed Cases

Apple's new programming language, Swift, allows two style of case statements: 1) one Enum case on each line, or 2) multiple Enum cases on a single line. Convert the following from the first case (no pun intended) to the second type.
** Start file
#+BEGIN_SRC 
enum PlaybackRequestType {
    case Next
    case Previous
    case Play
    case Stop
}
#+END_SRC

** End file
#+BEGIN_SRC 
enum PlaybackRequestType {
    case Next, Previous, Play, Stop
}
#+END_SRC

* Paragraph breaks
Swap the blank lines and the aaa lines.
** Start file

aa
a
aaa

aa
a
aaa

aa
a
aaa

aa
a

** End file

aa
a

aaa
aa
a

aaa
aa
a

aaa
aa
a

* Remember VimGolf Rules !

Rules, ... and don't forget !
** Start file
#+BEGIN_SRC 
Rules

1.Anyone can create a new challenge
2.Creator of the challenge is also the moderator: can view/delete solutions
3.Players can submit as many attempts as they want per challenge
4.Entries are ranked by score (lowest wins), ties broken by time
5.VimGolf initializes your Vim with a custom .vimrc - no custom modifications
6.No plugins, predefined macros, etc, are allowed - level playing field
7.Refrain from copy/paste, reading in the solution (:read), or using external tools
8.Cheaters will be publicly ridiculed by fellow golfers :-)

Note: We're definitely not trying to discourage Vim users from customizing their .vimrc's, defining useful macros or loading external plugins. Having said that, to have a fair competition, we need to level the playing field, and to do that, we're sticking to the basics.

A Happy New Year 2018 !
#+END_SRC

** End file
#+BEGIN_SRC 
Rules

1.Anyone can create a new challenge
2.Creator of the challenge is also the moderator: can view/delete solutions
3.Players can submit as many attempts as they want per challenge
4.Entries are ranked by score (lowest wins), ties broken by time
5.VimGolf initializes your Vim with a custom .vimrc - no custom modifications
6.No plugins, predefined macros, etc, are allowed - level playing field
7.Refrain from copy/paste, reading in the solution (:read), or using external tools
8.Cheaters will be publicly ridiculed by fellow golfers :-)

Note: We're definitely not trying to discourage Vim users from customizing their .vimrc's, defining useful macros or loading external plugins. Having said that, to have a fair competition, we need to level the playing field, and to do that, we're sticking to the basics.

A Happy New Year 2018 !!!!!!!!!!!!!!!!!!
#+END_SRC

* snowflake fractal

From step 0 to step 3 of a fractal
** Start file
#+BEGIN_SRC 
X
#+END_SRC

** End file
#+BEGIN_SRC 
X X   X X         X X   X X
 X     X           X     X
X X   X X         X X   X X
   X X               X X
    X                 X
   X X               X X
X X   X X         X X   X X
 X     X           X     X
X X   X X         X X   X X
         X X   X X
          X     X
         X X   X X
            X X
             X
            X X
         X X   X X
          X     X
         X X   X X
X X   X X         X X   X X
 X     X           X     X
X X   X X         X X   X X
   X X               X X
    X                 X
   X X               X X
X X   X X         X X   X X
 X     X           X     X
X X   X X         X X   X X
#+END_SRC

* Change the content of a string

This docstring is a complete lie. Fix it.
** Start file
#+BEGIN_SRC 
def add(a, b):
    """ Subtracts "x" from "y" """
    return a + b
#+END_SRC

** End file
#+BEGIN_SRC 
def add(a, b):
    """ Adds "a" to "b" """
    return a + b
#+END_SRC

* Alsa configuration

I'm tweaking my ~/.asoundrc file!
** Start file
#+BEGIN_SRC 
# dmix Plugin + Soft Volume
pcm.myconfig {
    type plug
    slave.pcm {
        type softvol
        control {
            name "Master Playback Vim"
            card 0
        }
        min_dB -19.0
        max_dB 10.2
        slave.pcm {
            @func concat
            strings [ "dmix:CARD=0,FORMAT=S16" ]
        }
    }
}
#+END_SRC

** End file
#+BEGIN_SRC 
# dmix Plugin + Soft Volume
pcm.myconfig {
    type plug
    slave.pcm {
        type softvol
        control {
            name "Master Playback Volume"
            card 0
        }
        min_dB -20.0
        max_dB 10.0
        slave.pcm "dmix:CARD=0,FORMAT=S16"
    }
}
#+END_SRC

* Gray area

It's a golf metaphor or something.
** Start file
#+BEGIN_SRC 
a_golf_ball - > - > - > - > |___________| -
#+END_SRC

** End file
#+BEGIN_SRC 
            - > - > - > - > |a_golf_ball| -
#+END_SRC

* Let's play some Ivmgolf

Oops, I spelled that wrong.
** Start file
#+BEGIN_SRC 
Ivm is an awesome text editor based on
Iv, and is used to play a game called
Ivmgolf. A challenge, simple for many
Ivmgolfers, can still hide secrets.
#+END_SRC

** End file
#+BEGIN_SRC 
Vim is an awesome text editor based on
Vi, and is used to play a game called
Vimgolf. A challenge, simple for many
Vimgolfers, can still hide secrets.
#+END_SRC

* The Cake is a Lie

Correct the capitalization of each word
** Start file
#+BEGIN_SRC 
tHE CakE iS A lIE
#+END_SRC

** End file
#+BEGIN_SRC 
The Cake is a Lie
#+END_SRC

* Two become one

We have two c arrays and want to make one two dimensional out of it. Can we do that?
** Start file
#+BEGIN_SRC 
/* Frame (32 bytes) */
static const unsigned char pkt1[32] = {
0x08, 0x60, 0x6e, 0xf1, 0x3c, 0xb9, 0x9c, 0xc7, /* .`n.<... */
0xa6, 0x35, 0x08, 0x12, 0x08, 0x00, 0x45, 0x00, /* .5....E. */
0x05, 0xdc, 0x1b, 0xe3, 0x40, 0x00, 0x31, 0x06, /* ....@.1. */
0xe8, 0xc8, 0xcb, 0xd9, 0x00, 0xda, 0xc0, 0xa8  /* ........ */
};

/* Frame (32 bytes) */
static const unsigned char pkt2[32] = {
0x08, 0x60, 0x6e, 0xf1, 0x3c, 0xb9, 0x9c, 0xc7, /* .`n.<... */
0xa6, 0x35, 0x08, 0x12, 0x08, 0x00, 0x45, 0x00, /* .5....E. */
0x05, 0xdc, 0x6b, 0x98, 0x40, 0x00, 0x31, 0x06, /* ..k.@.1. */
0x99, 0x13, 0xcb, 0xd9, 0x00, 0xda, 0xc0, 0xa8, /* ........ */
};
#+END_SRC

** End file
#+BEGIN_SRC 
/* Frame (32 bytes) */
static const unsigned char pkt1[2][32] = {
        {
        0x08, 0x60, 0x6e, 0xf1, 0x3c, 0xb9, 0x9c, 0xc7, /* .`n.<... */
        0xa6, 0x35, 0x08, 0x12, 0x08, 0x00, 0x45, 0x00, /* .5....E. */
        0x05, 0xdc, 0x1b, 0xe3, 0x40, 0x00, 0x31, 0x06, /* ....@.1. */
        0xe8, 0xc8, 0xcb, 0xd9, 0x00, 0xda, 0xc0, 0xa8  /* ........ */
        },
        {
        0x08, 0x60, 0x6e, 0xf1, 0x3c, 0xb9, 0x9c, 0xc7, /* .`n.<... */
        0xa6, 0x35, 0x08, 0x12, 0x08, 0x00, 0x45, 0x00, /* .5....E. */
        0x05, 0xdc, 0x6b, 0x98, 0x40, 0x00, 0x31, 0x06, /* ..k.@.1. */
        0x99, 0x13, 0xcb, 0xd9, 0x00, 0xda, 0xc0, 0xa8, /* ........ */
        }
};
#+END_SRC

* Create a table

Convert the given input into a formatted table
** Start file
#+BEGIN_SRC 
Item name            Quantity
Eggs                        2
Cucumber                   20
Watermelons                 1
#+END_SRC

** End file
#+BEGIN_SRC 
Item name   | Quantity
----------------------
Eggs        |        2
Cucumber    |       20
Watermelons |        1
#+END_SRC

* Sort and add attributes

Sort the states and add the attribute country to each record.
** Start file
#+BEGIN_SRC 
State.new(:name => "Ohio")
State.new(:name => "Wisconsin")
State.new(:name => "Iowa")
State.new(:name => "Virginia")
State.new(:name => "Utah")
State.new(:name => "Arizona")
State.new(:name => "Mississippi")
State.new(:name => "Michigan")
State.new(:name => "Virgin Islands")
State.new(:name => "Delaware")
State.new(:name => "North Carolina")
State.new(:name => "Montana")
State.new(:name => "Vermont")
State.new(:name => "New Jersey")
State.new(:name => "Illinois")
State.new(:name => "New Hampshire")
State.new(:name => "Kansas")
State.new(:name => "Texas")
State.new(:name => "Alabama")
State.new(:name => "Pennsylvania")
State.new(:name => "Louisiana")
State.new(:name => "Washington")
State.new(:name => "North Dakota")
State.new(:name => "Indiana")
State.new(:name => "South Carolina")
State.new(:name => "Hawaii")
State.new(:name => "Idaho")
State.new(:name => "Nebraska")
State.new(:name => "Tennessee")
State.new(:name => "Wyoming")
State.new(:name => "Colorado")
State.new(:name => "Rhode Island")
State.new(:name => "Connecticut")
State.new(:name => "Maryland")
State.new(:name => "Alaska")
State.new(:name => "Minnesota")
State.new(:name => "West Virginia")
State.new(:name => "Oklahoma")
State.new(:name => "Arkansas")
State.new(:name => "New Mexico")
State.new(:name => "Missouri")
State.new(:name => "Guam")
State.new(:name => "Maine")
State.new(:name => "New York")
State.new(:name => "Florida")
State.new(:name => "South Dakota")
State.new(:name => "Georgia")
State.new(:name => "Kentucky")
State.new(:name => "Oregon")
State.new(:name => "Nevada")
State.new(:name => "Massachusetts")
State.new(:name => "California")
#+END_SRC

** End file
#+BEGIN_SRC 
State.new(:name => "Alabama", :country => "USA")
State.new(:name => "Alaska", :country => "USA")
State.new(:name => "Arizona", :country => "USA")
State.new(:name => "Arkansas", :country => "USA")
State.new(:name => "California", :country => "USA")
State.new(:name => "Colorado", :country => "USA")
State.new(:name => "Connecticut", :country => "USA")
State.new(:name => "Delaware", :country => "USA")
State.new(:name => "Florida", :country => "USA")
State.new(:name => "Georgia", :country => "USA")
State.new(:name => "Guam", :country => "USA")
State.new(:name => "Hawaii", :country => "USA")
State.new(:name => "Idaho", :country => "USA")
State.new(:name => "Illinois", :country => "USA")
State.new(:name => "Indiana", :country => "USA")
State.new(:name => "Iowa", :country => "USA")
State.new(:name => "Kansas", :country => "USA")
State.new(:name => "Kentucky", :country => "USA")
State.new(:name => "Louisiana", :country => "USA")
State.new(:name => "Maine", :country => "USA")
State.new(:name => "Maryland", :country => "USA")
State.new(:name => "Massachusetts", :country => "USA")
State.new(:name => "Michigan", :country => "USA")
State.new(:name => "Minnesota", :country => "USA")
State.new(:name => "Mississippi", :country => "USA")
State.new(:name => "Missouri", :country => "USA")
State.new(:name => "Montana", :country => "USA")
State.new(:name => "Nebraska", :country => "USA")
State.new(:name => "Nevada", :country => "USA")
State.new(:name => "New Hampshire", :country => "USA")
State.new(:name => "New Jersey", :country => "USA")
State.new(:name => "New Mexico", :country => "USA")
State.new(:name => "New York", :country => "USA")
State.new(:name => "North Carolina", :country => "USA")
State.new(:name => "North Dakota", :country => "USA")
State.new(:name => "Ohio", :country => "USA")
State.new(:name => "Oklahoma", :country => "USA")
State.new(:name => "Oregon", :country => "USA")
State.new(:name => "Pennsylvania", :country => "USA")
State.new(:name => "Rhode Island", :country => "USA")
State.new(:name => "South Carolina", :country => "USA")
State.new(:name => "South Dakota", :country => "USA")
State.new(:name => "Tennessee", :country => "USA")
State.new(:name => "Texas", :country => "USA")
State.new(:name => "Utah", :country => "USA")
State.new(:name => "Vermont", :country => "USA")
State.new(:name => "Virgin Islands", :country => "USA")
State.new(:name => "Virginia", :country => "USA")
State.new(:name => "Washington", :country => "USA")
State.new(:name => "West Virginia", :country => "USA")
State.new(:name => "Wisconsin", :country => "USA")
State.new(:name => "Wyoming", :country => "USA")
#+END_SRC

* Ruby 1.9 hashes

Rubyists talk about being cutting edge but how many are using 1.9 in production? Time to convert those verbose 1.8 hashes in to symbolic, succinct 1.9 beauties!
** Start file
#+BEGIN_SRC 
{
  :a => 1,
  :b => 2,
  :c => 3
}
#+END_SRC

** End file
#+BEGIN_SRC 
{
  a: 1,
  b: 2,
  c: 3
}
#+END_SRC

* Append semicolon after expressions

Some lines need the semicolon, some don't.
** Start file
#+BEGIN_SRC 
var foo

var bar = myCoolStuff()

callRemote()

foo = callTheWorld()
#+END_SRC

** End file
#+BEGIN_SRC 
var foo;

var bar = myCoolStuff();

callRemote();

foo = callTheWorld();
#+END_SRC

* Reconstruct the Sentence

Get the sentence back in the proper order, remove duplicate lines, and then combine the separate lines into one.
** Start file
#+BEGIN_SRC 
time you're 7
in the 4
proper order 5
will be 2
by the 5
by the 5
put back 3
Vim! 10
done with 8
put back 3
This sentence 1
it in 9
#+END_SRC

** End file
#+BEGIN_SRC 
This sentence will be put back in the proper order by the time you're done with it in Vim!
#+END_SRC

* Simple addition
The right side of the equation is already there. We just need the left one now.
** Start file
#+BEGIN_SRC 
0
#+END_SRC

** End file
#+BEGIN_SRC 
10000-10000=0
#+END_SRC

* Hello ${world}

Migrate a JavaScript String from concatenation to ES6 interpolation.
** Start file
#+BEGIN_SRC 
let world = 'world';
console.log('hello ' + world);
console.log('bye ' + world + '!');
#+END_SRC

** End file
#+BEGIN_SRC 
let world = 'world';
console.log(`hello ${world}`);
console.log(`bye ${world}!`);
#+END_SRC

* Paragraph sort

My large herbivorous mammals, Vim commands, and POSIX utilities need to be sorted separately.
** Start file
#+BEGIN_SRC 
camel
elk
alpaca
deer
buffalo

buffer
delete
append
change
file
edit

date
chmod
awk
bc
#+END_SRC

** End file
#+BEGIN_SRC 
alpaca
buffalo
camel
deer
elk

append
buffer
change
delete
edit
file

awk
bc
chmod
date
#+END_SRC

* Stairstep digits

Remove the evens. Double the odds.
** Start file
#+BEGIN_SRC 
123456789
#+END_SRC

** End file
#+BEGIN_SRC 
1133557799
#+END_SRC

* Kolakoski sequence -- level 2

This time, the line above describes the line below. Level 1 at: http://www.vimgolf.com/challenges/5c880211ab65cb00065c74eb
** Start file
#+BEGIN_SRC 
12
#+END_SRC

** End file
#+BEGIN_SRC 
12
122
12211
1221121
1221121221
122112122122112
12211212212211211221211
1221121221221121122121121221121121
12211212212211211221211212211211212212211212212112
122112122122112112212112122112112122122112122121121122122112122122112112122
12211212212211211221211212211211212212211212212112112212211212212211211212212112212211212212211211221211212212211
#+END_SRC

* Nesting SASS

Move a block inside another block and indent it
** Start file
#+BEGIN_SRC 
.hero {
  background-color: pink;
}

header {
  border-bottom: 2px solid #26BBB3;
}
#+END_SRC

** End file
#+BEGIN_SRC 
.hero {
  background-color: pink;

  header {
    border-bottom: 2px solid #26BBB3;
  }
}
#+END_SRC

* Exchanging Quotes

Sometimes you need to exchange a choice of quotes in some code.
** Start file
#+BEGIN_SRC 
mystring = 'This quoted string contains \' and is also'
           'surrounded with \' characters.  It is also'
           'a multiline string too'
#+END_SRC

** End file
#+BEGIN_SRC 
mystring = "This quoted string contains ' and used to be"
           "surrounded with ' characters.  It is also"
           "a multiline string too"
#+END_SRC

* Make Fancy Header

Make the header text stand out with surrounding asterisks
** Start file
#+BEGIN_SRC 
Make this a fancy header
This is some text under the fancy header.

This is another fancy header
This is some more text
#+END_SRC

** End file
#+BEGIN_SRC 
***********************#+END_SRC
*
Make this a fancy header
************************
This is some text under the fancy header.

****************************
This is another fancy header
****************************
This is some more text
#+END_SRC

* Combines all items

For each line that starts with the same number I want to combine its contents
** Start file
#+BEGIN_SRC 
1 2472
1 664
2 2600
10 4135
10 5606
...
#+END_SRC

** End file
#+BEGIN_SRC 
1 2472 664
2 2600
10 4135 5606
...
#+END_SRC

* A Simple One

Here is a very simple one - just to illustrate/introduce a vim feature that some people seem to miss...
** Start file
#+BEGIN_SRC 
999 1999
#+END_SRC

** End file
#+BEGIN_SRC 
1024 2048
#+END_SRC

* Wrap text in quotes

All the blocks of text should be wrapped in quotation marks.
** Start file
#+BEGIN_SRC 
Fulfilled direction use continual set him propriety continued. Saw met applauded favourite deficient engrossed concealed and her.
Concluded boy perpetual old supposing. Farther related bed and passage comfort civilly. Dashwoods see frankness objection abilities the.
As hastened oh produced prospect formerly up am. Placing forming nay looking old married few has. Margaret disposed add screened rendered six
say his striking confined.

Any delicate you how kindness horrible outlived servants. You high bed wish help call draw side. Girl quit if case mr sing as no have.
At none neat am do over will. Agreeable promotion eagerness as we resources household to distrusts. Polite do object at passed it is.
Small for ask shade water manor think men begin.

Detract yet delight written farther his general. If in so bred at dare rose lose good. Feel and make two real miss use easy.
Celebrated delightful an especially increasing instrument am. Indulgence contrasted sufficient to unpleasant in in insensible favourable.
Latter remark hunted enough vulgar say man. Sitting hearted on it without me.

Domestic confined any but son bachelor advanced remember. How proceed offered her offence shy forming.
Returned peculiar pleasant but appetite differed she. Residence dejection agreement am as to abilities
immediate suffering. Ye am depending propriety sweetness distrusts belonging collected. Smiling mention
he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend.
Man its upon him call mile. An pasture he himself believe ferrars besides cottage.
#+END_SRC

** End file
#+BEGIN_SRC 
"Fulfilled direction use continual set him propriety continued. Saw met applauded favourite deficient engrossed concealed and her.
Concluded boy perpetual old supposing. Farther related bed and passage comfort civilly. Dashwoods see frankness objection abilities the.
As hastened oh produced prospect formerly up am. Placing forming nay looking old married few has. Margaret disposed add screened rendered six
say his striking confined."

"Any delicate you how kindness horrible outlived servants. You high bed wish help call draw side. Girl quit if case mr sing as no have.
At none neat am do over will. Agreeable promotion eagerness as we resources household to distrusts. Polite do object at passed it is.
Small for ask shade water manor think men begin."

"Detract yet delight written farther his general. If in so bred at dare rose lose good. Feel and make two real miss use easy.
Celebrated delightful an especially increasing instrument am. Indulgence contrasted sufficient to unpleasant in in insensible favourable.
Latter remark hunted enough vulgar say man. Sitting hearted on it without me."

"Domestic confined any but son bachelor advanced remember. How proceed offered her offence shy forming.
Returned peculiar pleasant but appetite differed she. Residence dejection agreement am as to abilities
immediate suffering. Ye am depending propriety sweetness distrusts belonging collected. Smiling mention
he in thought equally musical. Wisdom new and valley answer. Contented it so is discourse recommend.
Man its upon him call mile. An pasture he himself believe ferrars besides cottage."
#+END_SRC

* Replace and keep the case

Replace all instance of plugin and Plugin to device and Device.
** Start file
#+BEGIN_SRC 
 def plugin
    @plugin, @plugin_found_by = [Plugin.find_by_uid(@plugin_id), :uid] unless @plugin
    @plugin, @plugin_found_by = [Plugin.find_by_aid(@plugin_id), :aid] unless @plugin
    @plugin
 end
#+END_SRC

** End file
#+BEGIN_SRC 
 def device
    @device, @device_found_by = [Device.find_by_uid(@device_id), :uid] unless @device
    @device, @device_found_by = [Device.find_by_uid(@device_id), :uid] unless @device
    @device
 end
#+END_SRC

* Python Hello World! Reformatting

A novice Python using prints Hello World! and a pro shows him different way. Using vim to get into pro style from novice, win the challenge.
** Start file
#+BEGIN_SRC 
#!/usr/bin/python
import sys
a = "Hello World!"
sys.stdout.write(str(a[0]))
sys.stdout.write(str(a[1]))
sys.stdout.write(str(a[2]))
sys.stdout.write(str(a[3]))
sys.stdout.write(str(a[4]))
sys.stdout.write(str(a[5]))
sys.stdout.write(str(a[6]))
sys.stdout.write(str(a[7]))
sys.stdout.write(str(a[8]))
sys.stdout.write(str(a[9]))
sys.stdout.write(str(a[10]))
sys.stdout.write(str(a[11]))
#+END_SRC

** End file
#+BEGIN_SRC 
#!/usr/bin/python
import sys
a = "Hello World!"
for i in range(0, len(a)):
  sys.stdout.write(str(a[i]))
#+END_SRC

* Ugly spreadsheet copy/paste to CSV

convert an ugly spreadsheet copy/paste into a CSV format.
** Start file
#+BEGIN_SRC 
TIANJIN
DALIAN
HUANGPU
NINGBO
QINGDAO
SHANGHAI
SHANTOU
SHENZHEN
WUHAN
HONG KONG
HAIPHONG

885
885
910
860
885
860
1080
860
1040
860
935

1585
1585
1635
1535
1585
1535
1885
1535
1860
1535
1795

1710
1710
1760
1660
1610
1660
2010
1660
1985
1660
1920
#+END_SRC

** End file
#+BEGIN_SRC 
TIANJIN,885,1585,1710
DALIAN,885,1585,1710
HUANGPU,910,1635,1760
NINGBO,860,1535,1660
QINGDAO,885,1585,1610
SHANGHAI,860,1535,1660
SHANTOU,1080,1885,2010
SHENZHEN,860,1535,1660
WUHAN,1040,1860,1985
HONG KONG,860,1535,1660
HAIPHONG,935,1795,1920
#+END_SRC

* Flodder-challenge

Replace the text the most efficient and win!
** Start file
#+BEGIN_SRC 
Het fenoneem flodder begint in 1986 met de eerste Flodder-Film. De film trekt 2,3 miljoen bezoekers en in 1987 wint de film een gouden Kalf.
#+END_SRC

** End file
#+BEGIN_SRC 
het FENONEEM flodder BEGINT in 1986 MET de EERSTE flodder**film. DE film TREKT 2,3 miljoen bezoekers en in 1987 wint de film een GOUDEN Kalf.
#+END_SRC

* Mute the second method of this script

prepend a # infront of every line of the second method
** Start file
#+BEGIN_SRC 
def this_method_should_be_active
  here is happening something
end

def this_method_should_be_muted
  here is not happening anything
end
#+END_SRC

** End file
#+BEGIN_SRC 
def this_method_should_be_active
  here is happening something
end

#def this_method_should_be_muted
#  here is not happening anything
#end
#+END_SRC

* simple format (3)

reverse two column values!
** Start file
#+BEGIN_SRC 
one:1
two:2
three:3
four:4
five:5
six:6
seven:7
eight:8
nine:9
ten:10
#+END_SRC

** End file
#+BEGIN_SRC 
 1:        "one";
 2:        "two";
 3:      "three";
 4:       "four";
 5:       "five";
 6:        "six";
 7:      "seven";
 8:      "eight";
 9:       "nine";
10:        "ten";
#+END_SRC

* The name of the game

End up with the name of the game.
** Start file
#+BEGIN_SRC 
Victor india mike Golf oscar lima foxtrot
#+END_SRC

** End file
#+BEGIN_SRC 
VimGolf
#+END_SRC

* Interactive git rebase changing commands

How to change the action of some commits in git rebase dialog.
** Start file
#+BEGIN_SRC 
pick 6348363 fix(options) Remove hunglish titles
pick f80d2f6 fix(options) Style button focus state
pick 0f4aab2 feat(options) Highlight user color fields on hover
pick db11ec9 chore(build) Exclude applications key for chrome
pick 0569d27 chore(build) Create task to set version on build
pick 8e6ce65 fix(unlimited links) Add /treyblog to supported paths
pick d9b3279 fix(manifest) Typo in key and extension id
pick 3a2fb47 chore(build) Don't require hup.lh permissions
pick c42d63c Bump version to 2.4.0

# Rebase 87d11f5..c42d63c onto 87d11f5 (9 commands)
#
# Commands:
# p, pick = use commit
# r, reword = use commit, but edit the commit message
# e, edit = use commit, but stop for amending
# s, squash = use commit, but meld into previous commit
# f, fixup = like "squash", but discard this commit's log message
# x, exec = run command (the rest of the line) using shell
# d, drop = remove commit
#
# These lines can be re-ordered; they are executed from top to bottom.
#
# If you remove a line here THAT COMMIT WILL BE LOST.
#
# However, if you remove everything, the rebase will be aborted.
#
# Note that empty commits are commented out
#+END_SRC

** End file
#+BEGIN_SRC 
reword 6348363 fix(options) Remove hunglish titles
reword f80d2f6 fix(options) Style button focus state
reword 0f4aab2 feat(options) Highlight user color fields on hover
pick db11ec9 chore(build) Exclude applications key for chrome
pick 0569d27 chore(build) Create task to set version on build
reword 8e6ce65 fix(unlimited links) Add /treyblog to supported paths
reword d9b3279 fix(manifest) Typo in key and extension id
reword 3a2fb47 chore(build) Don't require hup.lh permissions
pick c42d63c Bump version to 2.4.0

# Rebase 87d11f5..c42d63c onto 87d11f5 (9 commands)
#
# Commands:
# p, pick = use commit
# r, reword = use commit, but edit the commit message
# e, edit = use commit, but stop for amending
# s, squash = use commit, but meld into previous commit
# f, fixup = like "squash", but discard this commit's log message
# x, exec = run command (the rest of the line) using shell
# d, drop = remove commit
#
# These lines can be re-ordered; they are executed from top to bottom.
#
# If you remove a line here THAT COMMIT WILL BE LOST.
#
# However, if you remove everything, the rebase will be aborted.
#
# Note that empty commits are commented out
#+END_SRC

* Generate a list of numbers

Please generate list of numbers from 1 to 20.
** Start file
#+BEGIN_SRC 
1
#+END_SRC

** End file
#+BEGIN_SRC 
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20
#+END_SRC

* Remove noise from HTTP log

This piece of log (from the year 2000) contains some irrelevant data. We only want to see the HTTP method and resource.
** Start file
#+BEGIN_SRC 
fcrawler.looksmart.com - - [26/Apr/2000:00:00:12 -0400] "GET /contacts.html HTTP/1.0" 200 4595 "-" "FAST-WebCrawler/2.1-pre2 (ashen@looksmart.net)"
fcrawler.looksmart.com - - [26/Apr/2000:00:17:19 -0400] "GET /news/news.html HTTP/1.0" 200 16716 "-" "FAST-WebCrawler/2.1-pre2 (ashen@looksmart.net)"
ppp931.on.bellglobal.com - - [26/Apr/2000:00:16:12 -0400] "GET /download/windows/asctab31.zip HTTP/1.0" 200 1540096 "http://www.htmlgoodies.com/downloads/freeware/webdevelopment/15.html" "Mozilla/4.7 [en]C-SYMPA  (Win95; U)"
123.123.123.123 - - [26/Apr/2000:00:23:48 -0400] "GET /pics/wpaper.gif HTTP/1.0" 200 6248 "http://www.jafsoft.com/asctortf/" "Mozilla/4.05 (Macintosh; I; PPC)"
123.123.123.123 - - [26/Apr/2000:00:23:47 -0400] "GET /asctortf/ HTTP/1.0" 200 8130 "http://search.netscape.com/Computers/Data_Formats/Document/Text/RTF" "Mozilla/4.05 (Macintosh; I; PPC)"
123.123.123.123 - - [26/Apr/2000:00:23:48 -0400] "GET /pics/5star2000.gif HTTP/1.0" 200 4005 "http://www.jafsoft.com/asctortf/" "Mozilla/4.05 (Macintosh; I; PPC)"
123.123.123.123 - - [26/Apr/2000:00:23:50 -0400] "GET /pics/5star.gif HTTP/1.0" 200 1031 "http://www.jafsoft.com/asctortf/" "Mozilla/4.05 (Macintosh; I; PPC)"
123.123.123.123 - - [26/Apr/2000:00:23:51 -0400] "GET /pics/a2hlogo.jpg HTTP/1.0" 200 4282 "http://www.jafsoft.com/asctortf/" "Mozilla/4.05 (Macintosh; I; PPC)"
123.123.123.123 - - [26/Apr/2000:00:23:51 -0400] "GET /cgi-bin/newcount?jafsof3&width=4&font=digital&noshow HTTP/1.0" 200 36 "http://www.jafsoft.com/asctortf/" "Mozilla/4.05 (Macintosh; I; PPC)"
#+END_SRC

** End file
#+BEGIN_SRC 
GET /contacts.html
GET /news/news.html
GET /download/windows/asctab31.zip
GET /pics/wpaper.gif
GET /asctortf/
GET /pics/5star2000.gif
GET /pics/5star.gif
GET /pics/a2hlogo.jpg
GET /cgi-bin/newcount?jafsof3&width=4&font=digital&noshow
#+END_SRC

* HTML to Haml

Help convert this HTML page to Haml.
** Start file
#+BEGIN_SRC 
<html>
  <head>
    <title>Vim Rocks!</title>
  </head>
  <body>
    <h1>So does Haml</h1>
  </body>
</html>
#+END_SRC

** End file
#+BEGIN_SRC 
%html
  %head
    %title Vim Rocks!
  %body
    %h1 So does Haml
#+END_SRC

* Reverse Simple Deletion

You did the simple deletion, now reverse it.
** Start file
#+BEGIN_SRC 
abcdefghijklmnopqrstuvwxyz
#+END_SRC

** End file
#+BEGIN_SRC 
a
b
c
d
e
f
g
h
i
j
k
l
m
n
o
p
q
r
s
t
u
v
w
x
y
z
#+END_SRC

* Assignment Alignment

line up the operators. Use spaces, not tabs.
** Start file
#+BEGIN_SRC 
# Align these assignments

x = 1
y = true
z = 'you'
foo = 'bar'
long_name = "long variable value"
$p3cial = ch4rs
last = line

# Much better!
#+END_SRC

** End file
#+BEGIN_SRC 
# Align these assignments

x         = 1
y         = true
z         = 'you'
foo       = 'bar'
long_name = "long variable value"
$p3cial   = ch4rs
last      = line

# Much better!
#+END_SRC

* Happy TvvO

Don’t forget the past, learn from it. Happy New Year.
** Start file
#+BEGIN_SRC 
Happy New Years to VIM !
#+END_SRC

** End file
#+BEGIN_SRC 
Happy New Years to vimgolf !
#+END_SRC

* VimGolfNight

Based on "The name of the game".
** Start file
#+BEGIN_SRC 
Victor india mike Golf oscar lima foxtrot November india golf hotel tango
#+END_SRC

** End file
#+BEGIN_SRC 
VimGolfNight
#+END_SRC

* Lisp Condense

Reduce 4 cons selection operations down to one function call.
** Start file
#+BEGIN_SRC 
(print (car (car (cdr (car list)))))
#+END_SRC

** End file
#+BEGIN_SRC 
(print (caadar list))
#+END_SRC

* Text to HTML Table

Turn the plain text table to an HTML table.
** Start file
#+BEGIN_SRC 
012
345
678
9ab
cde
 f 
#+END_SRC

** End file
#+BEGIN_SRC 
<table>
        <tr><td>0</td><td>1</td><td>2</td></tr>
        <tr><td>3</td><td>4</td><td>5</td></tr>
        <tr><td>6</td><td>7</td><td>8</td></tr>
        <tr><td>9</td><td>a</td><td>b</td></tr>
        <tr><td>c</td><td>d</td><td>e</td></tr>
        <tr><td> </td><td>f</td><td> </td></tr>
</table>
#+END_SRC

* Prefixes and suffixes

Generate all prefixes of "vimchallenge", then all suffixes.
** Start file
#+BEGIN_SRC 
vimchallenge
#+END_SRC

** End file
#+BEGIN_SRC 
vimchallenge
vimchalleng
vimchallen
vimchalle
vimchall
vimchal
vimcha
vimch
vimc
vim
vi
v

vimchallenge
imchallenge
mchallenge
challenge
hallenge
allenge
llenge
lenge
enge
nge
ge
e
#+END_SRC

* Swap assigned value

Simple problem but looking for interesting solutions.
** Start file
#+BEGIN_SRC 
app.config['CHALLENGE_FOLDER'] = SOLUTIONS_FOLDER
app.config['SOLUTIONS_FOLDER'] = CHALLENGE_FOLDER
#+END_SRC

** End file
#+BEGIN_SRC 
app.config['CHALLENGE_FOLDER'] = CHALLENGE_FOLDER
app.config['SOLUTIONS_FOLDER'] = SOLUTIONS_FOLDER
#+END_SRC

* Angular naming conventions

In angular, a directive name follows the camelCase convention. When the directive is used in an HTML template, the words are instead separated by a dash. Go from to the other the fastest!
** Start file
#+BEGIN_SRC 
Before I don't care greatDanesAreMyFriends After I don't care either
#+END_SRC

** End file
#+BEGIN_SRC 
Before I don't care great-danes-are-my-friends After I don't care either
#+END_SRC

* replace 2nd column blanks with values in same column if blank

Where ,SOMELOGB and ,SOMELOGC replaces each /r carriage return if 2nd column is blank. The replace only happens if 2nd column is blank though and should replace up to the non blank row.
** Start file
#+BEGIN_SRC 
TEST,SOMELOG
TESA,SOMELOGA
TESB
TESC
TESD,SOMELOGB
TESE
TESF
TESG,SOMELOGC
#+END_SRC

** End file
#+BEGIN_SRC 
TEST,SOMELOG
TESA,SOMELOGA
TESB,SOMELOGB
TESC,SOMELOGB
TESD,SOMELOGB
TESE,SOMELOGC
TESF,SOMELOGC
TESG,SOMELOGC
#+END_SRC

* Braces or Brackets?

Someone forgot whether to use braces or brackets and you have to clean up their code!
** Start file
#+BEGIN_SRC 
var some_function = function {arg1, arg2} [
        var some_array = (1, 2, 3, 4, 'foo');
        for {var i in some_array} (
                console.log(some_array, [{1 + (8 / 2)}, 'hello (world)');
        )
];
#+END_SRC

** End file
#+BEGIN_SRC 
var some_function = function (arg1, arg2) {
        var some_array = [1, 2, 3, 4, 'foo'];
        for (var i in some_array) {
                console.log(some_array, [(1 + (8 / 2)), 'hello (world)');
        }
};
#+END_SRC

* 120 Degrees

Rotate that triangle.
** Start file
#+BEGIN_SRC 
   1
  9 2
 8   3
7 6 5 4
#+END_SRC

** End file
#+BEGIN_SRC 
   4
  3 5
 2   6
1 9 8 7
#+END_SRC

* On Being Stylish

Your PR cannot be accepted if you don't follow our corporate style guide.
** Start file
#+BEGIN_SRC 
def fun(challenge, my_state, goal):
    """
    Wrapper around library magicks, there must be a better way to do this...
    """
    d = {
        "s_var": my_state.thing,
        "g_var": goal.state,
    }

    # TODO, break these lines up to fit our style guide
    long_yet_appropriately_precise_variable_name = lib.Magic(challenge.attribute, challenge.d["count"] - 1, descriptor=d)
    breakable_line = lib.Miscellaneous.ArcaneFactory.Magic(s_var=int(my_state.thing), g_var=int(goal.state), n=1, strict=True)
    return long_yet_appropriately_precise_variable_name
#+END_SRC

** End file
#+BEGIN_SRC 
def fun(challenge, my_state, goal):
    """
    Wrapper around library magicks, there must be a better way to do this...
    """
    d = {
        "s_var": my_state.thing,
        "g_var": goal.state,
    }

    # TODO, break these lines up to fit our style guide
    long_yet_appropriately_precise_variable_name = lib.Magic(
        challenge.attribute,
        challenge.d["count"] - 1,
        descriptor=d
    )
    breakable_line = lib.Miscellaneous.ArcaneFactory.Magic(
        s_var=int(my_state.thing),
        g_var=int(goal.state),
        n=1,
        strict=True
    )
    return long_yet_appropriately_precise_variable_name
#+END_SRC

* lamb had a little Mary

"Mary" and "lamb" are swapped. Unswap them. Fast as you can.
** Start file
#+BEGIN_SRC 
lamb had a little Mary,
Whose fleece was white as snow.
And everywhere that lamb went,
The Mary was sure to go.

It followed her to school one day,
Which was against the rule.
It made the children laugh and play,
To see a Mary at school.

And so the teacher turned it out,
But still it lingered near,
And waited patiently about,
Till lamb did appear.

"Why does the Mary love lamb so?"
The eager children cry.
"Why, lamb loves the Mary, you know."
The teacher did reply.
#+END_SRC

** End file
#+BEGIN_SRC 
Mary had a little lamb,
Whose fleece was white as snow.
And everywhere that Mary went,
The lamb was sure to go.

It followed her to school one day,
Which was against the rule.
It made the children laugh and play,
To see a lamb at school.

And so the teacher turned it out,
But still it lingered near,
And waited patiently about,
Till Mary did appear.

"Why does the lamb love Mary so?"
The eager children cry.
"Why, Mary loves the lamb, you know."
The teacher did reply.
#+END_SRC

* Minimalist Limerick

Reproduce this lovely poem.
** Start file
#+BEGIN_SRC 
 
#+END_SRC

** End file
#+BEGIN_SRC 
Word word word word word word word,
Word word word word word word word.
Word word word word word,
Word word word word word.
Word word word word word word word!
#+END_SRC

* Pretty multi-line bash

Bash line continuations are much prettier when they're column aligned.
** Start file
#+BEGIN_SRC 
RUN wget https://openresty.org/download/openresty-1.9.7.5.tar.gz && \
    tar xzf openresty-1.9.7.5.tar.gz && \
    cd openresty-1.9.7.5 && \
    ./configure && \
    make && \
    make install && \
    rm -rf /openresty*
#+END_SRC

** End file
#+BEGIN_SRC 
RUN wget https://openresty.org/download/openresty-1.9.7.5.tar.gz && \
    tar xzf openresty-1.9.7.5.tar.gz                             && \
    cd openresty-1.9.7.5                                         && \
    ./configure                                                  && \
    make                                                         && \
    make install                                                 && \
    rm -rf /openresty*#+END_SRC
#+END_SRC

* Add to end of each line... kinda

Visual-block mode can be used to add something to the end of each line, even if they are of differing lengths. However, what if it's not quite at the end?
** Start file
#+BEGIN_SRC 
function! FixLatexChars() 
        execute '%s/\\/\\textbackslash{}/c'
        execute '%s/#/\\#/c'
        execute '%s/\$/\\$/c'
        execute '%s/%/\\%/c'
        execute '%s/&/\\&/c'
        execute '%s/_/\\_/c'
endfunction
#+END_SRC

** End file
#+BEGIN_SRC 
function! FixLatexChars() 
        execute '%s/\\/\\textbackslash{}/ce'
        execute '%s/#/\\#/ce'
        execute '%s/\$/\\$/ce'
        execute '%s/%/\\%/ce'
        execute '%s/&/\\&/ce'
        execute '%s/_/\\_/ce'
endfunction
#+END_SRC

* readability

Make the code readable by adding some spaces
** Start file
#+BEGIN_SRC 
J=J-y(i)*log(h)-(1-y(i))*log(1-h)+(lambda/2)*sumtheta2;
#+END_SRC

** End file
#+BEGIN_SRC 
J = J - y(i) * log(h) - (1 - y(i)) * log(1 - h) + (lambda / 2) * sumtheta2;
#+END_SRC

* Line 'em up!

It can be so hard to keep everything neatly lined-up. Somebody clearly hasn't bothered here. Tidy it up, please!
** Start file
#+BEGIN_SRC 
foo {
    a   => "a",
    bc  => "bc",
    def => "def",
    ghij => "ghij",
    k => "k",
    lmn => "lmn",
    opqrst => "opqrst",
    uvw => "uvw",
    xyz => "xyz",
}
#+END_SRC

** End file
#+BEGIN_SRC 
foo {
    a       => "a",
    bc      => "bc",
    def     => "def",
    ghij    => "ghij",
    k       => "k",
    lmn     => "lmn",
    opqrst  => "opqrst",
    uvw     => "uvw",
    xyz     => "xyz",
}
#+END_SRC

* The meaning

Numbers are fun!
** Start file
#+BEGIN_SRC 
My favourite number is 24
#+END_SRC

** End file
#+BEGIN_SRC 
My favourite number is 42
#+END_SRC

* ASCII box

Don't forget to fix typos!
** Start file
#+BEGIN_SRC 
$ VimGold new challlenge
#+END_SRC

** End file
#+BEGIN_SRC 
                                *************************
                              #+END_SRC
  * VimGolf new challenge *
                                *************************

* imports alignment (python)

Align as one import per line.
** Start file
#+BEGIN_SRC 
from random import randint, uniform, shuffle, sample
from math import ceil, pow
#+END_SRC

** End file
#+BEGIN_SRC 
from random import randint
from random import uniform
from random import shuffle
from random import sample
from math import ceil
from math import pow
#+END_SRC

* Add Go XML to structure tags

The Go programming language can directly map XML to structure fields. Add the correct XML tag after each field.
** Start file
#+BEGIN_SRC 
package main

// FooXML mapping from XML to struct
type FooXML struct {
        Field1 string
        Field2 string
        Field3 string
}
#+END_SRC

** End file
#+BEGIN_SRC 
package main

// FooXML mapping from XML to struct
type FooXML struct {
        Field1 string `xml:"field1"`
        Field2 string `xml:"field2"`
        Field3 string `xml:"field3"`
}
#+END_SRC

* Separate the lines

Every other line is mixed up. Separate them into their original texts.
** Start file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, consectetur adipiscing elit,
Whose woods these are I think I know.
sed do eiusmod tempor incididunt ut labore et dolore magna
His house is in the village though;
aliqua. Ut enim ad minim veniam, quis nostrud exercitation
He will not see me stopping here
ullamco laboris nisi ut aliquip ex ea commodo consequat.
To watch his woods fill up with snow.
Duis aute irure dolor in reprehenderit in voluptate velit
My little horse must think it queer
esse cillum dolore eu fugiat nulla pariatur. Excepteur
To stop without a farmhouse near
sint occaecat cupidatat non proident, sunt in culpa qui
Between the woods and frozen lake
officia deserunt mollit anim id est laborum.
The darkest evening of the year.
#+END_SRC

** End file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, consectetur adipiscing elit,
sed do eiusmod tempor incididunt ut labore et dolore magna
aliqua. Ut enim ad minim veniam, quis nostrud exercitation
ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit
esse cillum dolore eu fugiat nulla pariatur. Excepteur
sint occaecat cupidatat non proident, sunt in culpa qui
officia deserunt mollit anim id est laborum.
Whose woods these are I think I know.
His house is in the village though;
He will not see me stopping here
To watch his woods fill up with snow.
My little horse must think it queer
To stop without a farmhouse near
Between the woods and frozen lake
The darkest evening of the year.
#+END_SRC
* lipsum lines

Convert a quoted block of text into strings in a list.
** Start file
#+BEGIN_SRC 
"Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt...
...ut labore et dolore magna aliqua.
Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris...
...nisi ut aliquip ex ea commodo consequat."
#+END_SRC

** End file
#+BEGIN_SRC 
lipsum = ["Lorem ipsum dolor sit amet,",
        "consectetur adipiscing elit,",
        "sed do eiusmod tempor incididunt...",
        "...ut labore et dolore magna aliqua.",
        "Ut enim ad minim veniam,",
        "quis nostrud exercitation ullamco laboris...",
        "...nisi ut aliquip ex ea commodo consequat."]
#+END_SRC

* Reverse characters in a line

You have everything you need, just not in the right order. Mastermind would give you 26 white pegs.
** Start file
#+BEGIN_SRC 
abcdefghijklmnopqrstuvwxyz
#+END_SRC

** End file
#+BEGIN_SRC 
zyxwvutsrqponmlkjihgfedcba
#+END_SRC

* Ruby 1.9 compat

Remember when Ruby supported `when <expr> :`? Well, it doesn't in 1.9, so let's make sure we use `then`, without ruining our lovely new hash syntax!
** Start file
#+BEGIN_SRC 
#!/usr/bin/env ruby

class Klass
  ITEMS = {
    foo: ["bar", "baz"],
    lorem: "ipsum",
  }

  def initialize(args)
    @item = case args.first
    when :foo, :bar: ITEMS[:foo][1]
    when :lorem    : ITEMS[:lorem]
    end
  end
end
#+END_SRC

** End file
#+BEGIN_SRC 
#!/usr/bin/env ruby

class Klass
  ITEMS = {
    foo: ["bar", "baz"],
    lorem: "ipsum",
  }

  def initialize(args)
    @item = case args.first
    when :foo, :bar then ITEMS[:foo][1]
    when :lorem     then ITEMS[:lorem]
    end
  end
end
#+END_SRC

* Logging with key

Sometimes it is better to log with meaningful key
** Start file
#+BEGIN_SRC 
window.nestedFormEvents.insertFields = (content, assoc, link) ->
  console.log content, assoc, link
#+END_SRC

** End file
#+BEGIN_SRC 
window.nestedFormEvents.insertFields = (content, assoc, link) ->
  console.log
    content: content
    assoc: assoc
    link: link
#+END_SRC

* Vim tetris

Vim can play tetris too!
** Start file
#+BEGIN_SRC 
|-------------------| Score: 0
|                   | Next:
|                   |   ##
|                   |   ##
|                   |
|                   |
|                   |
|     #             |
|     #             |
|     ##            |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|####   ############|
|  #################|
|###################|
|-------------------|
#+END_SRC

** End file
#+BEGIN_SRC 
|-------------------| Score: 1
|       ##          | Next:
|       ##          |   ##
|                   |  ##
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|                   |
|  #################|
|###################|
|-------------------|
#+END_SRC
* 7th Birthday

We have a bunch of numbers written from 0 to 9 in the order present in the text input file. The task is to create 7 by replacing the numbers with dashes.
** Start file
#+BEGIN_SRC 
12345678901234
23456789012345
34567890123456
45678901234567
56789012345678
67890123456789
78901234567890
89012345678901
90123456789012
#+END_SRC

** End file
#+BEGIN_SRC 
12-----------
2--56789012--5
3456789012--56
456789012--567
56789012--5678
6789012--56789
789012--567890
89012--5678901
9012--56789012
#+END_SRC

* vim = 22 / 7

pi square vim
** Start file
#+BEGIN_SRC 
vim
#+END_SRC

** End file
#+BEGIN_SRC 
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
 v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v  v
vimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvimvim
 m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m  m
#+END_SRC

* Remove semicolons after expressions

A follow-up for http://vimgolf.com/challenges/4fc9d767d3a0d4000100000e.
** Start file
#+BEGIN_SRC 
var foo;

var bar = myCoolStuff();

callRemote();

foo = callTheWorld();
#+END_SRC

** End file
#+BEGIN_SRC 
var foo

var bar = myCoolStuff()

callRemote()

foo = callTheWorld()
#+END_SRC

* Counting in binary

"a" represents 0; "A" represents 1. Start from zero and count to 15.
** Start file
#+BEGIN_SRC 
aaaa
#+END_SRC

** End file
#+BEGIN_SRC 
aaaa
aaaA
aaAa
aaAA
aAaa
aAaA
aAAa
aAAA
Aaaa
AaaA
AaAa
AaAA
AAaa
AAaA
AAAa
AAAA
#+END_SRC

* Remember FizzBuzz?

Output FizzBuzz to 100. Start with nothing.
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
3 Fizz
4
5 Buzz
6 Fizz
7
8
9 Fizz
10 Buzz
11
12 Fizz
13
14
15 FizzBuzz
16
17
18 Fizz
19
20 Buzz
21 Fizz
22
23
24 Fizz
25 Buzz
26
27 Fizz
28
29
30 FizzBuzz
31
32
33 Fizz
34
35 Buzz
36 Fizz
37
38
39 Fizz
40 Buzz
41
42 Fizz
43
44
45 FizzBuzz
46
47
48 Fizz
49
50 Buzz
51 Fizz
52
53
54 Fizz
55 Buzz
56
57 Fizz
58
59
60 FizzBuzz
61
62
63 Fizz
64
65 Buzz
66 Fizz
67
68
69 Fizz
70 Buzz
71
72 Fizz
73
74
75 FizzBuzz
76
77
78 Fizz
79
80 Buzz
81 Fizz
82
83
84 Fizz
85 Buzz
86
87 Fizz
88
89
90 FizzBuzz
91
92
93 Fizz
94
95 Buzz
96 Fizz
97
98
99 Fizz
100 Buzz
#+END_SRC

* Reformat most common surnames

Reformat copy-pasted table into a list of the most common surnames
** Start file
#+BEGIN_SRC 
Surname         Approx Number   % Frequency     Rank  
SMITH    2,501,922      1.006   1
JOHNSON  2,014,470      0.81    2
WILLIAMS         1,738,413      0.699   3
JONES    1,544,427      0.621   4
BROWN    1,544,427      0.621   5
DAVIS    1,193,760      0.48    6
MILLER   1,054,488      0.424   7
WILSON   843,093        0.339   8
MOORE    775,944        0.312   9
TAYLOR   773,457        0.311   10
#+END_SRC

** End file
#+BEGIN_SRC 
1. Smith
2. Johnson
3. Williams
4. Jones
5. Brown
6. Davis
7. Miller
8. Wilson
9. Moore
10. Taylor
#+END_SRC

* Interweave two blocks of text

Suppose you've got data on a list of things from multiple sources. They're all in separate chunks, so how might you create a tabular output?
** Start file
#+BEGIN_SRC 
one
two
three
four
five
six
seven
eight
nine
ten
1
2
3
4
5
6
7
8
9
10
#+END_SRC

** End file
#+BEGIN_SRC 
one     1
two     2
three   3
four    4
five    5
six     6
seven   7
eight   8
nine    9
ten     10
#+END_SRC

* Reformat some Python

Fix some very bizarrely laid-out code.
** Start file
#+BEGIN_SRC 
def fed(j):
    n = sum([1000000000,
              200000000,
               30000000,
                4000000,
                 500000,
                  60000,
                   7000,
                    800,
                     90,
                     j])
    print('abc'+str(n)+'def')
#+END_SRC

** End file
#+BEGIN_SRC 
def fed(j):
    n = 1234567890 + j
    print('abc%ddef' % n)
#+END_SRC

* Split the words

Add the spaces manually if you must, but if you use Vim's spell checking feature wisely, I think you'll save a LARGE number of strokes.
** Start file
#+BEGIN_SRC 
UseVim'sspellcheckfeaturetosplitthissentenceintowordsusingspaces.
 Vim: set spell:
#+END_SRC

** End file
#+BEGIN_SRC 
Use Vim's spell check feature to split this sentence into words using spaces.
 Vim: set spell:
#+END_SRC

* Shuffle puzzle

Sort the lines in each indent group, and sort the groups. That's the pattern. Or just move lines around manually to get a better score.
** Start file
#+BEGIN_SRC 
3
        4
        2
1
        3
        1
2
        5
        8
#+END_SRC

** End file
#+BEGIN_SRC 
1
        1
        3
2
        5
        8
3
        2
        4
#+END_SRC

* Un"finnish"ed Work

Replace å by a, ä by a and ö by o.
** Start file
#+BEGIN_SRC 
Åke käy mökillä.
#+END_SRC

** End file
#+BEGIN_SRC 
Ake kay mokilla.
#+END_SRC

* Reverse and double space

Reverse the order of the given lines and double space everything
** Start file
#+BEGIN_SRC 
1. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.
2. Nulla vitae elit libero, a pharetra augue. Donec sed odio dui.
3. Aenean eu leo quam.
4. Pellentesque ornare sem lacinia quam venenatis vestibulum.
5. Aenean lacinia bibendum nulla sed consectetur.
#+END_SRC

** End file
#+BEGIN_SRC 
5. Aenean lacinia bibendum nulla sed consectetur.

4. Pellentesque ornare sem lacinia quam venenatis vestibulum.

3. Aenean eu leo quam.

2. Nulla vitae elit libero, a pharetra augue. Donec sed odio dui.

1. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.
#+END_SRC

* NATO phonetic alphabet

Transform the series of words into a list.
** Start file
#+BEGIN_SRC 
Alfa Bravo Charlie Delta Echo Foxtrot Golf Hotel India Juliet Kilo Lima Mike November Oscar Papa Quebec Romeo Sierra Tengo Uniform Victor Whiskey Xray Yankee Zulu
#+END_SRC

** End file
#+BEGIN_SRC 
A = Alfa
B = Bravo
C = Charlie
D = Delta
E = Echo
F = Foxtrot
G = Golf
H = Hotel
I = India
J = Juliet
K = Kilo
L = Lima
M = Mike
N = November
O = Oscar
P = Papa
Q = Quebec
R = Romeo
S = Sierra
T = Tengo
U = Uniform
V = Victor
W = Whiskey
X = Xray
Y = Yankee
Z = Zulu
#+END_SRC

* Wrap the text of an email message to 79 characters

You're replying to an email with silly long lines. Clean them up.
** Start file
#+BEGIN_SRC 
> "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

> Sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
#+END_SRC

** End file
#+BEGIN_SRC 
> "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
> veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim
> ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

> Sed quia consequuntur magni dolores eos qui ratione voluptatem sequi
> nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet,
> consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt
> ut labore et dolore magnam aliquam quaerat voluptatem.

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit
laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure
reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur,
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
#+END_SRC

* Increment, increment, increment....

Vim likes macros
** Start file
#+BEGIN_SRC 
1
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
#+END_SRC

* Delete unwanted lines

Delete all lines which does not end in "o.."
** Start file
#+BEGIN_SRC 
gamag
gamah
ganci
gaoag
gaoah
gaoci
gbmag
gboch
gboci
gcmag
gcmah
gcmai
gcnci
gcoag
gcoah
gcoai
gcoch
gcobg
gcoci
hamag
hamah
hanci
haoag
hbmag
hbnci
hboag
hboch
hboci
hcmag
hcncg
hcnch
hcnci
hcoag
hcoci
iamag
#+END_SRC

** End file
#+BEGIN_SRC 
gaoag
gaoah
gaoci
gboch
gboci
gcoag
gcoah
gcoai
gcoch
gcobg
gcoci
haoag
hboag
hboch
hboci
hcoag
hcoci
#+END_SRC

* Subnetting

Split up the IP addresses in the right way.
** Start file
#+BEGIN_SRC 
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
37.192.0.0/13
#+END_SRC

** End file
#+BEGIN_SRC 
37.192.0.0/18
37.192.64.0/18
37.192.128.0/18
37.192.192.0/18
37.193.0.0/18
37.193.64.0/18
37.193.128.0/18
37.193.192.0/18
37.194.0.0/18
37.194.64.0/18
37.194.128.0/18
37.194.192.0/18
37.195.0.0/18
37.195.64.0/18
37.195.128.0/18
37.195.192.0/18
37.196.0.0/18
37.196.64.0/18
37.196.128.0/18
37.196.192.0/18
37.197.0.0/18
37.197.64.0/18
37.197.128.0/18
37.197.192.0/18
37.198.0.0/18
37.198.64.0/18
37.198.128.0/18
37.198.192.0/18
37.199.0.0/18
37.199.64.0/18
37.199.128.0/18
37.199.192.0/18
#+END_SRC

* Reformat a C golf submission

Take this C golf submission (for the "tiny but standards-compliant Hello World program" category, naturally), and turn it into formatted C code.
** Start file
#+BEGIN_SRC 
#include<stdio.h>
int main(void){puts("Hello world!");return 0;}
#+END_SRC

** End file
#+BEGIN_SRC 
#include <stdio.h>

int main(void)
{
    puts("Hello world!");
    return 0;
}
#+END_SRC

* Pairs of numbers

Line 1 represents x, line 2 y-data. Bring the corresponding pairs in the form "[x,y]\n"
** Start file
#+BEGIN_SRC 
0.173 0.499 0.764 0.938 1.000 0.927 0.527 0.000 -0.173 -0.499 -0.764 -0.938 -1.000 -0.927 -0.527 0.000
0.985 0.867 0.645 0.346 0.005 -0.376 -0.850 1.000 0.985 0.867 0.645 0.346 0.005 -0.376 -0.850 1.000
#+END_SRC

** End file
#+BEGIN_SRC 
[0.173, 0.985]
[0.499, 0.867]
[0.764, 0.645]
[0.938, 0.346]
[1.000, 0.005]
[0.927, -0.376]
[0.527, -0.850]
[0.000, 1.000]
[-0.173, 0.985]
[-0.499, 0.867]
[-0.764, 0.645]
[-0.938, 0.346]
[-1.000, 0.005]
[-0.927, -0.376]
[-0.527, -0.850]
[0.000, 1.000]
#+END_SRC

* Replacing some words

How fast could it be?
** Start file
#+BEGIN_SRC 
 4820 vim_golf  15   0 68772  11m  836 S  0.0  0.0   1:51.42 screen
 4821 vim_golf  16   0 54012 2288  900 S  0.0  0.0   0:00.09 tcsh
 4843 guestme   16   0 54360 2696  912 S  0.0  0.0   0:00.57 tcsh
 6602 vim_golf  16   0  374m 305m 203m S  0.0  0.4   0:02.85 gdb
 7599 vim_golf  16   0 53744 2000  864 S  0.0  0.0   0:00.63 tcsh
 7833 vim_golf  15   0 54032 2072  884 S  0.0  0.0   0:00.08 tcsh
11872 vim_golf  16   0 96100 5476 3812 S  0.0  0.0   0:00.04 vim
17605 vim_golf  16   0 53832 2012  820 S  0.0  0.0   0:00.07 tcsh
19698 vim_golf  16   0 35788 1744 1112 S  0.0  0.0   0:12.49 sshd
19699 vim_golf  15   0 54228 2084  912 S  0.0  0.0   0:00.07 tcsh
19731 vim_golf  16   0 58416  992  756 S  0.0  0.0   0:00.00 screen
23891 vim_golf  16   0  5584 1412  832 R  0.0  0.0  13:24.71 top
29880 vim_golf  16   0 54196 2320  924 S  0.0  0.0   0:00.63 tcsh
30558 vim_golf  16   0 98808 7652 4440 S  0.0  0.0   0:02.34 vim
30559 vim_golf  16   0     0    0    0 Z  0.0  0.0   0:00.00 cscope <defunct>
31131 vim_golf  16   0 53868 2148  896 S  0.0  0.0   0:00.10 tcsh
#+END_SRC

** End file
#+BEGIN_SRC 
 4820 vim_golf  15   0 68772  11m  836 S  0.0  0.0   1:51.42 screen
 4821 vim_golf  16   0 54012 2288  900 S  0.0  0.0   0:00.09 tcsh
 4843 guestme   16   0 54360 2696  912 S  0.0  0.0   0:00.57 tcsh
 6602 vim_golf  16   0  374m 305m 203m S  0.0  0.4   0:02.85 gdb
 7599 vim_golf  16   0 53744 2000  864 S  0.0  0.0   0:00.63 tcsh
 7833 vim_golf  15   0 54032 2072  884 S  0.0  0.0   0:00.08 tcsh
11872 vim_golf  16   0 96100 5476 3812 S  0.0  0.0   0:00.04 vim
17605 guestme   16   0 53832 2012  820 S  0.0  0.0   0:00.07 tcsh
19698 vim_golf  16   0 35788 1744 1112 S  0.0  0.0   0:12.49 sshd
19699 vim_golf  15   0 54228 2084  912 S  0.0  0.0   0:00.07 guestme
19731 vim_golf  16   0 58416  992  756 S  0.0  0.0   0:00.00 screen
23891 guestme   16   0  5584 1412  832 R  0.0  0.0  13:24.71 top
29880 vim_golf  16   0 54196 2320  924 S  0.0  0.0   0:00.63 tcsh
30558 vim_golf  16   0 98808 7652 4440 S  0.0  0.0   0:02.34 vim
30559 vim_golf  16   0     0    0    0 Z  0.0  0.0   0:00.00 cscope <defunct>
31131 vim_golf  16   0 53868 2148  896 S  0.0  0.0   0:00.10 tcsh
#+END_SRC

* Stairs Indenting

Indent each line with <line number> whitespaces.
** Start file
#+BEGIN_SRC 
1
2
3
4
5
6
7
8
9
10
#+END_SRC

** End file
#+BEGIN_SRC 
 1
  2
   3
    4
     5
      6
       7
        8
         9
          10
#+END_SRC

* For all cases.

In this case... change it! :) Watch the line.
** Start file
#+BEGIN_SRC 
tHIS tEXT hAS aLL tHE cAPS tHE wRONG wAY
And you should fix that please.
----------------------------------------
#+END_SRC

** End file
#+BEGIN_SRC 
This Text Has All The Caps The Wrong Way
And you should fix that please.
========================================
#+END_SRC

* A simple change

Just change the numbers in the most efficient way ...
** Start file
#+BEGIN_SRC 
1024 2048 3072 4096 5120
6144 7168 8192 9216
#+END_SRC

** End file
#+BEGIN_SRC 
2048 3072 4096 5120 6144
7168 8192 9216 10240
#+END_SRC

* PHP Array Syntax -> MailChimp Merge Syntax

I recently needed to send an e-mail to our marketing department listing allowed merge tags for our MailChimp campaigns. The allowed merge tags were determined from a PHP array in one of our PHP classes. I transformed the PHP class to MailChimp's syntax and sent the e-mail. It was, however, a long, laborious process. I'm still fairly new to Vim and would love to see how an expert Vim user would tackle one of my own, real-world problems. Thanks and have fun!
** Start file
#+BEGIN_SRC 
$allowed = array("PIN", "Prefix", "LastName", "FirstName", "MiddleName", 
  "Address1", "Address2", "City", "State", "Zip", "Country", "phone", "mobile",
  "Email", "MothersMaiden", "security1_id", "security1_answer", 
  "security2_id", "security2_answer", "BirthDate", 
  "flag1", "DriversLicense", "gender");
#+END_SRC

** End file
#+BEGIN_SRC 
*|PIN|#+END_SRC
*
*|Prefix|*
*|LastName|*
*|FirstName|*
*|MiddleName|*
*|Address1|*
*|Address2|*
*|City|*
*|State|*
*|Zip|*
*|Country|*
*|phone|*
*|mobile|*
*|Email|*
*|MothersMaiden|*
*|security1_id|*
*|security1_answer|*
*|security2_id|*
*|security2_answer|*
*|BirthDate|*
*|flag1|*
*|DriversLicense|*
*|gender|*
#+END_SRC

* Context insensitive completion 0

Buried in the lines you're not supposed to add is the line "Add this line!" Add that line to the top of the file.
** Start file
#+BEGIN_SRC 
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Add this line!
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
#+END_SRC

** End file
#+BEGIN_SRC 
Add this line!
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Add this line!
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
Do not add this line.
#+END_SRC

* Sorting paragraphs

Order the paragraphs correctly, per prefixed index
** Start file
#+BEGIN_SRC 
4) Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla feugiat placerat odio. 
Praesent tempus, enim eget fermentum dictum, libero ante commodo enim, a adipiscing arcu arcu et erat. 
Ut ipsum neque, ornare nec condimentum a, feugiat et felis.

3) Nam vehicula velit mollis arcu vulputate tempus. Sed lobortis ante non ligula aliquet elementum.
Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Phasellus pharetra, 
orci id commodo malesuada, mauris dolor viverra felis, eget euismod libero turpis vel nisi.

2) Phasellus mauris ipsum, placerat nec pellentesque ac, tristique vitae risus. 
Mauris rhoncus erat at eros feugiat blandit. Nulla facilisi. Vivamus semper blandit viverra. 
Mauris quis arcu quis purus feugiat auctor.

6) Sed id eros quis metus pellentesque pellentesque eget quis erat. Curabitur quis sapien turpis, sed ullamcorper 
ipsum. In hac habitasse platea dictumst. Sed quis elit eu elit congue vestibulum. Duis tincidunt pellentesque 
convallis. Mauris accumsan suscipit placerat. Nullam mattis vulputate enim non volutpat.

1) Morbi ultricies arcu erat. Praesent iaculis fermentum odio, in suscipit lorem congue id. 
Sed euismod felis nec ipsum laoreet et suscipit justo vulputate. Donec lorem odio, lobortis ut 
scelerisque sed, interdum nec augue.

5) Aenean in lorem mi. Mauris ac eros mi. In accumsan urna eu nibh euismod non imperdiet quam fringilla. 
Integer orci massa, mattis adipiscing commodo vel, cursus in lorem.
#+END_SRC

** End file
#+BEGIN_SRC 
1) Morbi ultricies arcu erat. Praesent iaculis fermentum odio, in suscipit lorem congue id. 
Sed euismod felis nec ipsum laoreet et suscipit justo vulputate. Donec lorem odio, lobortis ut 
scelerisque sed, interdum nec augue.

2) Phasellus mauris ipsum, placerat nec pellentesque ac, tristique vitae risus. 
Mauris rhoncus erat at eros feugiat blandit. Nulla facilisi. Vivamus semper blandit viverra. 
Mauris quis arcu quis purus feugiat auctor.

3) Nam vehicula velit mollis arcu vulputate tempus. Sed lobortis ante non ligula aliquet elementum.
Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Phasellus pharetra, 
orci id commodo malesuada, mauris dolor viverra felis, eget euismod libero turpis vel nisi.

4) Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla feugiat placerat odio. 
Praesent tempus, enim eget fermentum dictum, libero ante commodo enim, a adipiscing arcu arcu et erat. 
Ut ipsum neque, ornare nec condimentum a, feugiat et felis.

5) Aenean in lorem mi. Mauris ac eros mi. In accumsan urna eu nibh euismod non imperdiet quam fringilla. 
Integer orci massa, mattis adipiscing commodo vel, cursus in lorem.

6) Sed id eros quis metus pellentesque pellentesque eget quis erat. Curabitur quis sapien turpis, sed ullamcorper 
ipsum. In hac habitasse platea dictumst. Sed quis elit eu elit congue vestibulum. Duis tincidunt pellentesque 
convallis. Mauris accumsan suscipit placerat. Nullam mattis vulputate enim non volutpat.
#+END_SRC

* Add fold markers to a .c file

Fold markers can make it easier to navigate source code. Add them to this .c file.
** Start file
#+BEGIN_SRC 
#include <string.h>
#include <stdio.h>
#include <stdlib.h>
#include <assert.h>

void copy(char *to, char *from, size_t count) {
    register n=(count+7)/8;
    switch(count%8){
    case 0: do{     *to = *from++;
    case 7:         *to = *from++;
    case 6:         *to = *from++;
    case 5:         *to = *from++;
    case 4:         *to = *from++;
    case 3:         *to = *from++;
    case 2:         *to = *from++;
    case 1:         *to = *from++;
            }while(--n>0);
    }
}

int main() {
    char *input = malloc(sizeof(char) * 1024);
    assert(input);
    char *output = malloc(sizeof(char) * 1024);
    assert(output);
    copy(output, input, sizeof(char) * 1024);
    return 0;
}
#+END_SRC

** End file
#+BEGIN_SRC 
#include <string.h>/*{{{*/
#include <stdio.h>
#include <stdlib.h>
#include <assert.h>
/*}}}*/

void copy(char *to, char *from, size_t count) {/*{{{*/
    register n=(count+7)/8;
    switch(count%8){
    case 0: do{     *to = *from++;
    case 7:         *to = *from++;
    case 6:         *to = *from++;
    case 5:         *to = *from++;
    case 4:         *to = *from++;
    case 3:         *to = *from++;
    case 2:         *to = *from++;
    case 1:         *to = *from++;
            }while(--n>0);
    }
}/*}}}*/

int main() {/*{{{*/
    char *input = malloc(sizeof(char) * 1024);
    assert(input);
    char *output = malloc(sizeof(char) * 1024);
    assert(output);
    copy(output, input, sizeof(char) * 1024);
    return 0;
}/*}}}*/
#+END_SRC

* Sort files from hosts

Resume files by host. I hope you enjoy with this challenge
** Start file
#+BEGIN_SRC 
dartacan: /etc/hosts
dartacan: /etc/httpd/conf/httpd.conf
dartacan: /opt/scripts/list_vhosts
mozart: /etc/resolv.conf
mozart: /usr/bin/vim
mozart: /usr/bin/awesome
mozart: ~/.gem/ruby/2.1.0/bin/vimgolf
gullit: /bin/bash
gullit: /etc/hosts
gullit: /usr/bin/xorg
gullit: /usr/bin/xeyes
gullit: /usr/bin/X
gullit: /
#+END_SRC

** End file
#+BEGIN_SRC 
dartacan: /etc/hosts /etc/httpd/conf/httpd.conf /opt/scripts/list_vhosts
mozart: /etc/resolv.conf /usr/bin/vim /usr/bin/awesome ~/.gem/ruby/2.1.0/bin/vimgolf
gullit: /bin/bash /etc/hosts /usr/bin/xorg /usr/bin/xeyes /usr/bin/X /
#+END_SRC

* Going underground....

Simple reformatting: in this case changing from the format London underground supplies its customers with, to the format that Google Calendar likes...
** Start file
#+BEGIN_SRC 
Date,Start Time,End Time,Journey/Action,Charge,Credit,Balance,Note
23-Nov-2013,12:16,12:38,"Bermondsey to West Hampstead [London Underground]",2.10,,26.50,""
23-Nov-2013,09:38,10:02,"West Hampstead [London Underground] to Bermondsey",2.10,,8.60,""
20-Nov-2013,23:14,23:43,"Kennington to West Hampstead [London Underground]",1.40,,10.70,"The fare for this journey was capped as you reached the daily charging limit for the zones used"
20-Nov-2013,20:53,,"Bus journey, route 159",1.40,,12.10,""
20-Nov-2013,20:27,20:50,"Warwick Avenue to Lambeth North",2.10,,13.50,""
20-Nov-2013,17:57,18:19,"West Hampstead [London Underground] to Paddington (Bakerloo, Circle/District and H&C)",2.10,,15.60,""
18-Nov-2013,17:37,17:48,"Kensal Rise to West Hampstead [London Overground]",1.60,,24.90,""
18-Nov-2013,17:31,,"Bus journey, route 6",1.40,,26.50,""
18-Nov-2013,16:16,,"Bus journey, route 6",1.40,,27.90,""
#+END_SRC

** End file
#+BEGIN_SRC 
Date,Start Time,End Time,Journey/Action,Charge,Credit,Balance,Note
23-Nov-2013,12:16-12:38,"Bermondsey to West Hampstead [London Underground]"
23-Nov-2013,09:38-10:02,"West Hampstead [London Underground] to Bermondsey"
20-Nov-2013,23:14-23:43,"Kennington to West Hampstead [London Underground]"
20-Nov-2013,20:53,"Bus journey, route 159"
20-Nov-2013,20:27-20:50,"Warwick Avenue to Lambeth North"
20-Nov-2013,17:57-18:19,"West Hampstead [London Underground] to Paddington (Bakerloo, Circle/District and H&C)"
18-Nov-2013,17:37-17:48,"Kensal Rise to West Hampstead [London Overground]"
18-Nov-2013,17:31,"Bus journey, route 6"
18-Nov-2013,16:16,"Bus journey, route 6"
#+END_SRC

* Indentation

Indent each line according to the right number of spaces it needs.
** Start file
#+BEGIN_SRC 
this line doesn’t have indentation
this line is indented with two spaces
this one has four
this other one has two
this one is indented with two spaces
this line has a four spaces indentation
this line needs six spaces
this line needs six spaces too
this line is back to four spaces
this line is finally indented with two spaces
this final line is not indented
#+END_SRC

** End file
#+BEGIN_SRC 
this line doesn’t have indentation
  this line is indented with two spaces
    this one has four
  this other one has two
  this one is indented with two spaces
    this line has a four spaces indentation
      this line needs six spaces
      this line needs six spaces too
    this line is back to four spaces
  this line is finally indented with two spaces
this final line is not indented
#+END_SRC

* Line Zipper

Zip/pair related lines.
** Start file
#+BEGIN_SRC 
China,1,2,3,4,5,6
Brazil,3,1,2,5,5,6
SAD,9,2,3,4,5,6
UK,3,8,3,9,5,1
France,7,2,3,4,5,6
Germany,1,7,3,2,5,6
Russia,1,6,2,9,5,6
Spain,1,2,2,4,5,6
Greece,1,3,3,4,5,6
India,4,2,3,4,5,6
Turkey,1,2,3,4,5,9
Poland,1,2,3,4,5,6
China,1,2,3,8,5,6
Brazil,1,2,3,4,5,6
SAD,1,2,3,4,5,6
UK,1,2,3,4,5,6
France,1,2,3,4,5,6
Germany,1,2,3,4,5,6
Russia,1,2,7,4,5,6
Spain,1,2,3,4,5,6
Greece,1,2,2,4,5,6
India,1,2,8,4,5,6
Turkey,1,2,1,7,5,6
Poland,2,2,3,9,5,6
#+END_SRC

** End file
#+BEGIN_SRC 
China,1,2,3,8,5,6
China,1,2,3,4,5,6
Brazil,1,2,3,4,5,6
Brazil,3,1,2,5,5,6
SAD,1,2,3,4,5,6
SAD,9,2,3,4,5,6
UK,1,2,3,4,5,6
UK,3,8,3,9,5,1
France,1,2,3,4,5,6
France,7,2,3,4,5,6
Germany,1,2,3,4,5,6
Germany,1,7,3,2,5,6
Russia,1,2,7,4,5,6
Russia,1,6,2,9,5,6
Spain,1,2,3,4,5,6
Spain,1,2,2,4,5,6
Greece,1,2,2,4,5,6
Greece,1,3,3,4,5,6
India,1,2,8,4,5,6
India,4,2,3,4,5,6
Turkey,1,2,1,7,5,6
Turkey,1,2,3,4,5,9
Poland,2,2,3,9,5,6
Poland,1,2,3,4,5,6
#+END_SRC

* Shuffled numbers

Each number is paired with the number it should follow. That's enough information to put them in order.
** Start file
#+BEGIN_SRC 
nine: eight
twelve: eleven
seventeen: sixteen
nineteen: eighteen
two: one
twenty: nineteen
five: four
eighteen: seventeen
one: -
sixteen: fifteen
thirteen: twelve
three: two
eight: seven
ten: nine
six: five
fourteen: thirteen
fifteen: fourteen
four: three
seven: six
eleven: ten
#+END_SRC

** End file
#+BEGIN_SRC 
one: -
two: one
three: two
four: three
five: four
six: five
seven: six
eight: seven
nine: eight
ten: nine
eleven: ten
twelve: eleven
thirteen: twelve
fourteen: thirteen
fifteen: fourteen
sixteen: fifteen
seventeen: sixteen
eighteen: seventeen
nineteen: eighteen
twenty: nineteen
#+END_SRC

* vim1001

change number 1001 into a "vim1001 sequence". (My first challenge, hope it is not too bad... )
** Start file
#+BEGIN_SRC 
1001
#+END_SRC

** End file
#+BEGIN_SRC 
vim1001
vim1005
vim1011
vim1015
vim1021
vim1025
vim1031
vim1035
vim1041
vim1045
#+END_SRC

* Mirrored text

backward and forward, and long enough to be challenging
** Start file
#+BEGIN_SRC 
qwertyuiopasdfghjkl;zxcvbnm,./
#+END_SRC

** End file
#+BEGIN_SRC 
/.,mnbvcxz;lkjhgfdsapoiuytrewqqwertyuiopasdfghjkl;zxcvbnm,./
#+END_SRC

* The Quick Brown Fox Jumps Over The Lazy Vim

Someone has vandalized this text file and replaced the beginning character of one word in each line with a Big "X." Please remove the big X's, and fix each line to read "The Quick Brown Fox Jumps Over The Lazy Dog."
** Start file
#+BEGIN_SRC 
Xhe Quick Brown Fox Jumps Over The Lazy Dog.
The Xuick Brown Fox Jumps Over The Lazy Dog.
The Quick Xrown Fox Jumps Over The Lazy Dog.
The Quick Brown Xox Jumps Over The Lazy Dog.
The Quick Brown Fox Xumps Over The Lazy Dog.
The Quick Brown Fox Jumps Xver The Lazy Dog.
The Quick Brown Fox Jumps Over Xhe Lazy Dog.
The Quick Brown Fox Jumps Over The Xazy Dog.
The Quick Brown Fox Jumps Over The Lazy Xog.
The Quick Brown Fox Jumps Over The Lazy Xog.
The Quick Brown Fox Jumps Over The Xazy Dog.
The Quick Brown Fox Jumps Over Xhe Lazy Dog.
The Quick Brown Fox Jumps Xver The Lazy Dog.
The Quick Brown Fox Xumps Over The Lazy Dog.
The Quick Brown Xox Jumps Over The Lazy Dog.
The Quick Xrown Fox Jumps Over The Lazy Dog.
The Xuick Brown Fox Jumps Over The Lazy Dog.
Xhe Quick Brown Fox Jumps Over The Lazy Dog.
#+END_SRC

** End file
#+BEGIN_SRC 
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
The Quick Brown Fox Jumps Over The Lazy Dog.
#+END_SRC

* Generate English Alphabets

Start with a, get up to z.
** Start file
#+BEGIN_SRC 
a
#+END_SRC

** End file
#+BEGIN_SRC 
a
b
c
d
e
f
g
h
i
j
k
l
m
n
o
p
q
r
s
t
u
v
w
x
y
z
#+END_SRC

* you're stuck on jQuery < 1.7

replace calls to jQuery 1.7+'s `on` with calls to pre 1.7 `bind`
** Start file
#+BEGIN_SRC 
    $('li.assessment_question').on('click', 'a.add_question_addendum', @openQuestionAddendumForm)
    $('li.assessment_question').on('click', 'a.cancel_question_addendum', @cancelQuestionAddendum)
    $('li.assessment_question').on('ajax:beforeSend', 'form.question_addendum_form', @hideFormEnableAddAddendumLink)
    $('li.assessment_question').on('ajax:success', 'form.question_addendum_form', @appendQuestionAddendum)
#+END_SRC

** End file
#+BEGIN_SRC 
    $('a.add_question_addendum').bind('click', @openQuestionAddendumForm)
    $('a.cancel_question_addendum').bind('click', @cancelQuestionAddendum)
    $('form.question_addendum_form').bind('ajax:beforeSend', @hideFormEnableAddAddendumLink)
    $('form.question_addendum_form').bind('ajax:success', @appendQuestionAddendum)
#+END_SRC
* Case preserving word replacement

Half way through my project, my people turned into dogs. Now I have to change everything in my source.
** Start file
#+BEGIN_SRC 
function Human() {

}

Human.prototype = {
        humanStuff: function(){},
        doHumanStuff: function() {
                useDigitalWatch();
        }
}
#+END_SRC

** End file
#+BEGIN_SRC 
function Dog() {

}

Dog.prototype = {
        dogStuff: function(){},
        doDogStuff: function() {
                useDigitalWatch();
        }
}
#+END_SRC

* FoodCritic023: Prefer conditional attributes

FoodCritic (www.foodcritic.io) is a lint tool for your Chef (learn.chef.io) cookbooks. FC023 indicates that you should prefer Chef guards over Ruby conditions. This challenge expects you to be able to fix this issue in a sample cookbook, given the FoodCritic output: ================================================================ FC023: Prefer conditional attributes: cookbooks/foo/recipes/default.rb:25 ================================================================ See http://www.foodcritic.io/#FC023 for more details about the changes being made.
** Start file
#+BEGIN_SRC 
# Cookbook Name:: foo
# Recipe:: default
#
# Copyright 2015, Foo Inc.
#
# All rights reserved - Do Not Redistribute
#

directory "/opt/foo" do
end

remote_file "/tmp/foo.rpm" do
  source "http://foo.inc/packages/foo.rpm"
  action :create
end

rpm_package "/tmp/foo.rpm" do
  action :install
end

service "foo" do
  action :start
end

if node["foo"] == "bar"
  execute "bar my foo" do
    command "foo < bar"
  end
end
#+END_SRC

** End file
#+BEGIN_SRC 
# Cookbook Name:: foo
# Recipe:: default
#
# Copyright 2015, Foo Inc.
#
# All rights reserved - Do Not Redistribute
#

directory "/opt/foo" do
end

remote_file "/tmp/foo.rpm" do
  source "http://foo.inc/packages/foo.rpm"
  action :create
end

rpm_package "/tmp/foo.rpm" do
  action :install
end

service "foo" do
  action :start
end

execute "bar my foo" do
  command "foo < bar"
  only_if { node["foo"] == "bar" }
end
#+END_SRC
* Start coding format

I used to start coding with following format: int main(){ -(cursor here) }
** Start file
#+BEGIN_SRC 
_
#+END_SRC

** End file
#+BEGIN_SRC 
int main(){
    _
}
#+END_SRC

* Context Insensitive completion 1

Finish writing this simple Python HTTP server.
** Start file
#+BEGIN_SRC 
from SimpleHTTPServer import SimpleHTTPRequestHandler
from SocketServer import TCPServer

ADDR = ("", 8080)
httpd = # Finish this line
httpd.serve_forever()
#+END_SRC

** End file
#+BEGIN_SRC 
from SimpleHTTPServer import SimpleHTTPRequestHandler
from SocketServer import TCPServer

ADDR = ("", 8080)
httpd = TCPServer(ADDR, SimpleHTTPRequestHandler)
httpd.serve_forever()
#+END_SRC

* Insert a Markdown link

Put a link in a markdown document, using the after-the-paragraph format.
** Start file
#+BEGIN_SRC 
Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you
to write using an easy-to-read, easy-to-write plain text format, then convert
it to structurally valid XHTML (or HTML).
#+END_SRC

** End file
#+BEGIN_SRC 
Markdown is a text-to-HTML conversion tool for web writers. [Markdown][] allows you
to write using an easy-to-read, easy-to-write plain text format, then convert
it to structurally valid XHTML (or HTML).

    [Markdown]:
#+END_SRC

* NBCU Weekly Challenge - Test

Just testing.
** Start file
#+BEGIN_SRC 
The reabbit is fasster than the fox.
#+END_SRC

** End file
#+BEGIN_SRC 
The rabbit is faster than the turtle.
#+END_SRC

* Reverse and count

Someone typed things upside down and now a Vim ninja needs to reverse the lines and count how many there are.
** Start file
#+BEGIN_SRC 
Sixth line
Fifth line
Fourth line
Third line
Second line
First line
#+END_SRC

** End file
#+BEGIN_SRC 
1. First line
2. Second line
3. Third line
4. Fourth line
5. Fifth line
6. Sixth line
#+END_SRC

* Sorting database text output

Sometimes it is nice to be able to quickly take column-formatted text output from the SQL command line and turn it into a list of useful data. In this case we want a unique, sorted list of the values from the second column combined into one comma-separated list. What is the fewest strokes you can do this in?
** Start file
#+BEGIN_SRC 
      0 |    1
      0 |   24
      1 |    1
      1 |    2
      1 |    3
      1 |    4
      1 |   15
      1 |   24
      1 |   62
      1 |  107
      2 |    1
      2 |    2
      2 |    8
      2 |   15
      2 |   18
      2 |   25
      2 |   28
      2 |   47
      2 |   65
      2 |   69
      2 |   76
      2 |   99
      2 |  103
      2 |  110
      2 |  153
      3 |    3
      3 |   32
      3 |   49
      3 |   65
      3 |   76
      3 |   96
      4 |    2
#+END_SRC

** End file
#+BEGIN_SRC 
1, 2, 3, 4, 8, 15, 18, 24, 25, 28, 32, 47, 49, 62, 65, 69, 76, 96, 99, 103, 107, 110, 153
#+END_SRC
* underscore_to_camelCase

Pointy haired boss decided we need to switch to camelCase. Let's get this over with.
** Start file
#+BEGIN_SRC 
log(req, res, next) {
    try {
        let ratio = this.config.get("HEADER_LOG_FREQ", 0.05);
        if (Math.random() < ratio) {
            this.arrange_headers(req, res).then(this.write_log);
        }
        let safe_path = this.safe_graphite_path(req.path);
        this.stats.increment("web.endpoint." + safe_path, 1, 0.05);
        if (req.headers && req.headers["x-forwarded-proto"]) {
            this.stats.increment("web.protocol." + req.headers["x-forwarded-proto"], 1, 0.05);
        }
    } catch (error) {
        log.warning(error, "Failed to log headers");
        res.status(500).send("its_not_you_its_me");
    } finally {
        next();
    }
}
#+END_SRC

** End file
#+BEGIN_SRC 
log(req, res, next) {
    try {
        let ratio = this.config.get("HEADER_LOG_FREQ", 0.05);
        if (Math.random() < ratio) {
            this.arrangeHeaders(req, res).then(this.writeLog);
        }
        let safePath = this.safeGraphitePath(req.path);
        this.stats.increment("web.endpoint." + safePath, 1, 0.05);
        if (req.headers && req.headers["x-forwarded-proto"]) {
            this.stats.increment("web.protocol." + req.headers["x-forwarded-proto"], 1, 0.05);
        }
    } catch (error) {
        log.warning(error, "Failed to log headers");
        res.status(500).send("its_not_you_its_me");
    } finally {
        next();
    }
}
#+END_SRC
* JS notation to Immutable.js notation

Now Immutable.js made its way into many frontends. This challenge consists of a typical refactoring that many of us are facing now.
** Start file
#+BEGIN_SRC 
lines[1][1] = 'hello'
lines[2][0] = 'world'
lines[3][1] = 'whats'
lines[10][2] = 'going'
lines[12][1] = 'on'
#+END_SRC

** End file
#+BEGIN_SRC 
lines
        .setIn([1, 1], 'hello')
        .setIn([2, 0], 'world')
        .setIn([3, 1], 'whats')
        .setIn([10, 2], 'going')
        .setIn([12, 1], 'on')
#+END_SRC

* Hatsuyume

http://en.wikipedia.org/wiki/Hatsuyume
** Start file
#+BEGIN_SRC 
Hatsuyume

Fuji
Taka
Nasubi

Sen
Tabako
Zatō
#+END_SRC

** End file
#+BEGIN_SRC 
Hatsuyume

1 Fuji
2 Taka
3 Nasubi

4 Sen
5 Tabako
6 Zatō
#+END_SRC

* Vim's not included features

Filter not included (-) features in a hypothetical installation of vim.
** Start file
#+BEGIN_SRC 
+acl             +farsi           +mouse_netterm   +syntax
+arabic          +file_in_path    +mouse_sgr       +tag_binary
+autocmd         +find_in_path    -mouse_sysmouse  +tag_old_static
-balloon_eval    +float           +mouse_urxvt     -tag_any_white
-browse          +folding         +mouse_xterm     -tcl
++builtin_terms  -footer          +multi_byte      +terminfo
+byte_offset     +fork()          +multi_lang      +termresponse
+cindent         -gettext         -mzscheme        +textobjects
-clientserver    -hangul_input    +netbeans_intg   +title
+clipboard       +iconv           +path_extra      -toolbar
+cmdline_compl   +insert_expand   +perl            +user_commands
+cmdline_hist    +jumplist        +persistent_undo +vertsplit
+cmdline_info    +keymap          +postscript      +virtualedit
+comments        +langmap         +printer         +visual
+conceal         +libcall         +profile         +visualextra
+cryptv          +linebreak       +python          +viminfo
+cscope          +lispindent      -python3         +vreplace
+cursorbind      +listcmds        +quickfix        +wildignore
+cursorshape     +localmap        +reltime         +wildmenu
+dialog_con      -lua             +rightleft       +windows
+diff            +menu            +ruby            +writebackup
+digraphs        +mksession       +scrollbind      -X11
-dnd             +modify_fname    +signs           -xfontset
-ebcdic          +mouse           +smartindent     -xim
+emacs_tags      -mouseshape      -sniff           -xsmp
+eval            +mouse_dec       +startuptime     -xterm_clipboard
+ex_extra        -mouse_gpm       +statusline      -xterm_save
+extra_search    -mouse_jsbterm   -sun_workshop    -xpm
#+END_SRC

** End file
#+BEGIN_SRC 
-balloon_eval
-browse
-clientserver
-dnd
-ebcdic
-footer
-gettext
-hangul_input
-lua
-mouseshape
-mouse_gpm
-mouse_jsbterm
-mouse_sysmouse
-mzscheme
-python3
-sniff
-sun_workshop
-tag_any_white
-tcl
-toolbar
-X11
-xfontset
-xim
-xsmp
-xterm_clipboard
-xterm_save
-xpm
#+END_SRC

* Rotating Philosophers Problem

Can you help the philosophers find a good place to sit before they get five forks and spaghetti?
** Start file
#+BEGIN_SRC 
Socrates Voltaire Descartes Plato
#+END_SRC

** End file
#+BEGIN_SRC 
Socrates Voltaire Descartes Plato Konfuzius
Konfuzius Socrates Voltaire Descartes Plato
Plato Konfuzius Socrates Voltaire Descartes
Descartes Plato Konfuzius Socrates Voltaire
Voltaire Descartes Plato Konfuzius Socrates
#+END_SRC

* Sort the VimGolf challenges by popularity

"Sort by popularity" is a good order to play the challenges. Not perfect, but you could do a lot worse. ;) Input is a sample copy-pasted from vimgolf.com. Some of the challenge names have digits that will get in your way, so read ":help :sort" for hints on sorting with a regex. When you're done, try your solution on the full list!
** Start file
#+BEGIN_SRC 
replacing each line of a block selection - 809 entries

replace each line's ../assets/js with /javascripts
switch variable - 1197 entries

how fast can you switch two variable ?
Numbering a List - 914 entries

Pretty simple, number the list.
Context Insensitive completion 1 - 304 entries

Finish writing this simple Python HTTP server.
Search and Replace 0 - 1442 entries

Replace every instance of 'aaa' with 'xaaax'.
Wrap the text of an email message to 79 characters - 351 entries

You're replying to an email with silly long lines. Clean them up.
Sort and add attributes - 754 entries

Sort the states and add the attribute country to each record.
Whitespace, empty lines and tabs - 1470 entries

Convert tabs to spaces, strip empty lines and trailing whitespace.
Simple text editing with Vim - 3405 entries

Make the pairs of lines match up by making each second line same as first
Reformat/Refactor a Golfer Class - 2803 entries

A simple case of removing unneeded code and fixing broken indentation.
#+END_SRC

** End file
#+BEGIN_SRC 
Simple text editing with Vim - 3405 entries
Reformat/Refactor a Golfer Class - 2803 entries
Whitespace, empty lines and tabs - 1470 entries
Search and Replace 0 - 1442 entries
switch variable - 1197 entries
Numbering a List - 914 entries
replacing each line of a block selection - 809 entries
Sort and add attributes - 754 entries
Wrap the text of an email message to 79 characters - 351 entries
Context Insensitive completion 1 - 304 entries
#+END_SRC
* Array of characters

We all copy paste things off the internet, but the syntax doesn't look right. Fix it as fast as possible.
** Start file
#+BEGIN_SRC 
# pound < left angle bracket    $ dollar sign   + plus sign
% percent       > right angle bracket   ! exclamation point     ` backtick
& ampersand     * asterisk      ' single quotes | pipe
{ left bracket  ? question mark = equal sign
} right bracket / forward slash : colon  
  blank spaces  @ at sign
#+END_SRC

** End file
#+BEGIN_SRC 
["#", "<", "$", "+", "%", ">", "!", "`", "&", "*", "'", "|", "{", "?", "=", "}", "/", ":", " ", "@"]
#+END_SRC

* A grid of punctuation

Create a checkerboard of = and - in an 80×24 grid!
** Start file
#+BEGIN_SRC 
-=
#+END_SRC

** End file
#+BEGIN_SRC 
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-
#+END_SRC

* Sort entries based on date

Sort some entries in a Ledger-file based on date.
** Start file
#+BEGIN_SRC 
10.09.2011 Description
  Some
  Stuff

15.09.2011 * Anything really
  Random
  Stuff

12.10.2011 Nice
  Not
  Kidding

12.09.2011 Whatever
  Anything
  Can
  Be
  Here

14.09.2011 Cool
  But
  It's always
  Indented

13.09.2011 Testing
  Always
  2 spaces
#+END_SRC

** End file 
#+BEGIN_SRC
10.09.2011 Description
  Some
  Stuff

12.09.2011 Whatever
  Anything
  Can
  Be
  Here

13.09.2011 Testing
  Always
  2 spaces

14.09.2011 Cool
  But
  It's always
  Indented

15.09.2011 * Anything really
  Random
  Stuff

12.10.2011 Nice
  Not
  Kidding * Change your calendar
#+END_SRC

* Happy New Year!
** Start file
#+BEGIN_SRC 
    January 2012
Su Mo Tu We Th Fr Sa
 1  2  3  4  5  6  7
 8  9 10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30 31
#+END_SRC

** End file
#+BEGIN_SRC 
    January 2013
Su Mo Tu We Th Fr Sa
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31
#+END_SRC
#+END_SRC

* Restore order to the alphabet

The numbers are OK. The letters are wonky.
** Start file
#+BEGIN_SRC 
0a
1b
2j
3d
4i
5g
6h
7c
8e
9f
10k
11l
12m
13n
14o
15p
16q
17r
18s
19t
#+END_SRC

** End file
#+BEGIN_SRC 
0a
1b
2c
3d
4e
5f
6g
7h
8i
9j
10k
11l
12m
13n
14o
15p
16q
17r
18s
19t
#+END_SRC

* Neither Fizz nor Buzz

Not your regular increment macro! The gaps are tricky.
** Start file
#+BEGIN_SRC 
0
0
Fizz
0
Buzz
Fizz
0
0
Fizz
Buzz
0
Fizz
0
0
FizzBuzz
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
#+END_SRC

* learn vim in short time

so happy to learn vim.because vim is awesome
** Start file
#+BEGIN_SRC 
input.file
#+END_SRC

** End file
#+BEGIN_SRC 
output.file
#+END_SRC

* Refactor static member invocation

Someone used a static method. Refactor the method into a static import while fixing the assertion.
** Start file
#+BEGIN_SRC 
import org.Assert;

C{
        m(){
                Assert.assertEquals(42, "Meaning of life");
        }
}
#+END_SRC

** End file
#+BEGIN_SRC 
import static org.Assert.assertEquals;

C{
        m(){
                assertEquals("Meaning of life", "Meaning of life");
        }
}
#+END_SRC

* Table Reshuffle

Fix the column order in this table... also append the new 'username' column.
** Start file
#+BEGIN_SRC 
smith,john,27
brown,bob,35
jones,steve,19
graham,phil,44
#+END_SRC

** End file
#+BEGIN_SRC 
27,john,smith,jsmith
35,bob,brown,bbrown
19,steve,jones,sjones
44,phil,graham,pgraham
#+END_SRC

* Reformat long lines

Rearrange this ruby method call to put each parameter on its own line. Could become a useful macro.
** Start file
#+BEGIN_SRC 
def default_i18n_subject
  mailer_scope = self.class.mailer_name.gsub('/', '.')
  I18n.t(:subject, :scope => [mailer_scope, action_name], :default => action_name.humanize)
end
#+END_SRC

** End file
#+BEGIN_SRC 
def default_i18n_subject
  mailer_scope = self.class.mailer_name.gsub('/', '.')
  I18n.t(:subject,
         :scope => [mailer_scope, action_name],
         :default => action_name.humanize)
end
#+END_SRC

* abcd > a b c d

transform the single spaces into 4 spaces repeat for each line
** Start file
#+BEGIN_SRC 
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
#+END_SRC

** End file
#+BEGIN_SRC 
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
a    b    c    d    e    f    g    h    i    j    k    l    m    n    o    p    q    r    s    t    u    v    w    x    y    z
#+END_SRC

* Shift down

Number words are back.
** Start file
#+BEGIN_SRC 
one two three

four five six

seven eight nine
#+END_SRC

** End file
#+BEGIN_SRC 
one
    two
        three

four
     five
          six

seven
      eight
            nine
#+END_SRC

* Get rid of html tags

Want to read more about Vim's background? Then get rid of those html tags...
** Start file
#+BEGIN_SRC 
<h1>What Vim Can Do</h1> 
<p> 
Vim is an advanced text editor that seeks to provide the power of
the de-facto Unix editor 'Vi', with a more complete feature set.
It's useful whether you're <a href='viusers.php'>already using vi</a> or <a
href='others.php'>using a different editor</a>.  Users of Vim 5 and 6 should
consider upgrading to Vim 7.  The main advantages of Vim 6 compared to Vim 5 
can be found on <a href='vim5users.php'>this page</a>.
</p> 
 
<h1>A General Overview</h1> 
 
<a href="http://tnerual.eriogerg.free.fr/0xBABAF000L/10_en.html"><img src='/images/0xbabaf000l.png' alt="Emaks-Vim-Notepad comic" width="800" height="254"></a> 
Copyright (c) 2007 Laurent Gregoire
 
<h4>What Is Vim?</h4> 
<p> 
Vim is a highly configurable text editor built to enable efficient text
editing. It is an improved version of the vi editor distributed with
most UNIX systems.  
<p> 
Vim is often called a "programmer's editor," and so useful for
programming that many consider it an entire <abbr title='integrated
development environment'>IDE</abbr>.  It's not just for programmers,
though.  Vim is perfect for all kinds of text editing, from composing
email to editing configuration files.
</p> 
<p> 
Despite what the above comic suggests, Vim can be configured to work in a very
simple (Notepad-like) way, called evim or Easy Vim.
</p> 
 
<h4>What Vim Is Not?</h4> 
<p> 
Vim isn't an editor designed to hold its users' hands.  It is a tool,
the use of which must be learned.
</p> 
 
<p> 
Vim isn't a word processor.  Although it can display text with various
forms of highlighting and formatting, it isn't there to provide WYSIWYG
editing of typeset documents.  (It is great for editing TeX, though.)
</p> 
 
<h4>Vim's License</h4> 
<p> 
Vim is charityware.  Its license is GPL-compatible, so it's
distributed freely, but we ask that if you find it useful you make a
donation to help children in Uganda through the
<a href='http://iccf-holland.org/'>ICCF</a>.  The full license text can be
found in the <a href='http://vimdoc.sourceforge.net/htmldoc/uganda.html#license'>documentation</a>.
Much more information about charityware on
<A HREF="http://Charityware.info/">Charityware.info</a>.
</p> 
#+END_SRC

** End file
#+BEGIN_SRC 
What Vim Can Do 
 
Vim is an advanced text editor that seeks to provide the power of
the de-facto Unix editor 'Vi', with a more complete feature set.
It's useful whether you're already using vi or <a
href='others.php'>using a different editor.  Users of Vim 5 and 6 should
consider upgrading to Vim 7.  The main advantages of Vim 6 compared to Vim 5 
can be found on this page.
 
 
A General Overview 
 
 
Copyright (c) 2007 Laurent Gregoire
 
What Is Vim? 
 
Vim is a highly configurable text editor built to enable efficient text
editing. It is an improved version of the vi editor distributed with
most UNIX systems.  
 
Vim is often called a "programmer's editor," and so useful for
programming that many consider it an entire <abbr title='integrated
development environment'>IDE.  It's not just for programmers,
though.  Vim is perfect for all kinds of text editing, from composing
email to editing configuration files.
 
 
Despite what the above comic suggests, Vim can be configured to work in a very
simple (Notepad-like) way, called evim or Easy Vim.
 
 
What Vim Is Not? 
 
Vim isn't an editor designed to hold its users' hands.  It is a tool,
the use of which must be learned.
 
 
 
Vim isn't a word processor.  Although it can display text with various
forms of highlighting and formatting, it isn't there to provide WYSIWYG
editing of typeset documents.  (It is great for editing TeX, though.)
 
 
Vim's License 
 
Vim is charityware.  Its license is GPL-compatible, so it's
distributed freely, but we ask that if you find it useful you make a
donation to help children in Uganda through the
ICCF.  The full license text can be
found in the documentation.
Much more information about charityware on
Charityware.info.
#+END_SRC
* Change attribute to getter

Wrap attributes with a getter method.
** Start file
#+BEGIN_SRC 
function() {
  var a = thing.index < other.attribute;
  var b = thing.index < other.attribute;
  var c = thing.attribute < other.index;
  var d = thing.attribute < other.index;
}
#+END_SRC

** End file
#+BEGIN_SRC 
function() {
  var a = thing.get('index') < other.get('attribute');
  var b = thing.get('index') < other.get('attribute');
  var c = thing.get('attribute') < other.get('index');
  var d = thing.get('attribute') < other.get('index');
}
#+END_SRC

* remove all lines in first part

From the second part, remove all lines in the first part. It can be useful when you have done something from a long list, you want to know what is not done yet!
** Start file
#+BEGIN_SRC 
vim = 22 / 7
A simple change
Basic renumbering
Just the middle
Search and Replace 0
That hyphen
Space out the alphabet
Do you demand a shrubbery?
Ugly spreadsheet copy/paste to CSV
Sort and add attributes
Simple text editing with Vim
Don't know what this is
Fix the XML

Shuffled numbers
camel riding
Just the middle
I forgot quotes
A HAPPY NEW YEAR 2014 !
Fix the XML
Words in parens
Basic renumbering
Space out the alphabet
V to the i
Simple text editing with Vim
-a-b-c-
That hyphen
Don't know what this is
ASCII box
Gray area
Where should I put the Newline?
Search and Replace 0
Do you demand a shrubbery?
Saving the hashes(#)
Vertical Limit
Separating firstname & lastname
Test everything!
Sort and add attributes
Ugly spreadsheet copy/paste to CSV
vim = 22 / 7
Subtraction
A simple change
you're stuck on jQuery < 1.7
PHP Array Syntax -> MailChimp Merge Syntax
#+END_SRC

** End file
#+BEGIN_SRC 
Shuffled numbers
camel riding
I forgot quotes
A HAPPY NEW YEAR 2014 !
Words in parens
V to the i
-a-b-c-
ASCII box
Gray area
Where should I put the Newline?
Saving the hashes(#)
Vertical Limit
Separating firstname & lastname
Test everything!
Subtraction
you're stuck on jQuery < 1.7
PHP Array Syntax -> MailChimp Merge Syntax
#+END_SRC
* Wget failed to download redirections

Output of a wget session, where 302 where not properly handled due to certificate problems, has been saved to a file. Keep the correct URLs to start again downloading.
** Start file
#+BEGIN_SRC 
--2015-01-04 17:52:38--  https://archive.org/download/Man_Who_Cheated_Himself/Man_Who_Cheated_Himself.ogv
Resolving archive.org... 207.241.224.2
Connecting to archive.org|207.241.224.2|:443... connected.
HTTP request sent, awaiting response... 302 Moved Temporarily
Location: https://ia700401.us.archive.org/4/items/Man_Who_Cheated_Himself/Man_Who_Cheated_Himself.ogv [following]
--2015-01-04 17:52:39--  https://ia700401.us.archive.org/4/items/Man_Who_Cheated_Himself/Man_Who_Cheated_Himself.ogv
Resolving ia700401.us.archive.org... 207.241.228.50
Connecting to ia700401.us.archive.org|207.241.228.50|:443... connected.
ERROR: no certificate subject alternative name matches
        requested host name `ia700401.us.archive.org'.
To connect to ia700401.us.archive.org insecurely, use `--no-check-certificate'.
--2015-01-04 18:01:21--  https://archive.org/download/ScarletStreet/Scarlet_Street_512kb.mp4
Resolving archive.org... 207.241.224.2
Connecting to archive.org|207.241.224.2|:443... connected.
HTTP request sent, awaiting response... 302 Moved Temporarily
Location: https://ia902300.us.archive.org/25/items/ScarletStreet/Scarlet_Street_512kb.mp4 [following]
--2015-01-04 18:01:22--  https://ia902300.us.archive.org/25/items/ScarletStreet/Scarlet_Street_512kb.mp4
Resolving ia902300.us.archive.org... 207.241.228.50
Connecting to ia902300.us.archive.org|207.241.228.50|:443... connected.
ERROR: no certificate subject alternative name matches
        requested host name `ia902300.us.archive.org'.
To connect to ia902300.us.archive.org insecurely, use `--no-check-certificate'.
--2015-01-04 18:01:23--  https://archive.org/download/Timetable1956/Timetable1956.mp4
Resolving archive.org... 207.241.224.2
Connecting to archive.org|207.241.224.2|:443... connected.
HTTP request sent, awaiting response... 302 Moved Temporarily
Location: https://ia600801.us.archive.org/4/items/Timetable1956/Timetable1956.mp4 [following]
--2015-01-04 18:01:24--  https://ia600801.us.archive.org/4/items/Timetable1956/Timetable1956.mp4
Resolving ia600801.us.archive.org... 207.241.227.151
Connecting to ia600801.us.archive.org|207.241.227.151|:443... connected.
ERROR: no certificate subject alternative name matches
        requested host name `ia600801.us.archive.org'.
To connect to ia600801.us.archive.org insecurely, use `--no-check-certificate'.
--2015-01-04 18:01:25--  https://archive.org/download/TooLateForTears/TooLateForTears.mp4
Resolving archive.org... 207.241.224.2
Connecting to archive.org|207.241.224.2|:443... connected.
HTTP request sent, awaiting response... 302 Moved Temporarily
Location: https://ia600409.us.archive.org/13/items/TooLateForTears/TooLateForTears.mp4 [following]
--2015-01-04 18:01:27--  https://ia600409.us.archive.org/13/items/TooLateForTears/TooLateForTears.mp4
Resolving ia600409.us.archive.org... 207.241.227.219
Connecting to ia600409.us.archive.org|207.241.227.219|:443... connected.
ERROR: no certificate subject alternative name matches
        requested host name `ia600409.us.archive.org'.
To connect to ia600409.us.archive.org insecurely, use `--no-check-certificate'.
--2015-01-04 18:01:28--  https://archive.org/download/Quicksand_clear/Quicksand_512kb.mp4
Resolving archive.org... 207.241.224.2
Connecting to archive.org|207.241.224.2|:443... connected.
HTTP request sent, awaiting response... 302 Moved Temporarily
Location: https://ia600406.us.archive.org/14/items/Quicksand_clear/Quicksand_512kb.mp4 [following]
--2015-01-04 18:01:29--  https://ia600406.us.archive.org/14/items/Quicksand_clear/Quicksand_512kb.mp4
Resolving ia600406.us.archive.org... 207.241.227.216
Connecting to ia600406.us.archive.org|207.241.227.216|:443... connected.
ERROR: no certificate subject alternative name matches
        requested host name `ia600406.us.archive.org'.
To connect to ia600406.us.archive.org insecurely, use `--no-check-certificate'.
#+END_SRC

** End file
#+BEGIN_SRC 
https://ia700401.us.archive.org/4/items/Man_Who_Cheated_Himself/Man_Who_Cheated_Himself.ogv
https://ia902300.us.archive.org/25/items/ScarletStreet/Scarlet_Street_512kb.mp4
https://ia600801.us.archive.org/4/items/Timetable1956/Timetable1956.mp4
https://ia600409.us.archive.org/13/items/TooLateForTears/TooLateForTears.mp4
https://ia600406.us.archive.org/14/items/Quicksand_clear/Quicksand_512kb.mp4
#+END_SRC

* Free hyphen!

Just like "Inner hyphens", but I'm giving you a free hyphen to play with. Will your solution be any different?
** Start file
#+BEGIN_SRC 
-abcdef
#+END_SRC

** End file
#+BEGIN_SRC 
a-b-c-d-e-f
#+END_SRC

* The holy-grail may help

Can you find it in less than 20 strokes, Arthur?
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
You found it, Arthur!
#+END_SRC

* Inner hyphens

Yet another hyphen challenge. Adding 5 hyphens to a file shouldn't be too hard.
** Start file
#+BEGIN_SRC 
abcdef
#+END_SRC

** End file
#+BEGIN_SRC 
a-b-c-d-e-f
#+END_SRC

* Readable Rubyhash

Rubyists talk about being cutting edge but how many are using 1.9 in production? Time to convert those verbose 1.8 hashes in to symbolic, succinct 1.9 beauties!
** Start file
#+BEGIN_SRC 
{:a=>1,:b=>2,:c=>3}
#+END_SRC

** End file
#+BEGIN_SRC 
{
  a: 1,
  b: 2,
  c: 3
}
#+END_SRC

* Suffix sort

Sort from the end of the line, as if the letters in each line were reversed.
** Start file
#+BEGIN_SRC 
adjutants
ametropic
audiobook
blockable
demagogic
embryotic
excusable
garroters
housesits
labellers
opacifier
proofroom
quercetin
rejudging
supremely
#+END_SRC

** End file
#+BEGIN_SRC 
demagogic
ametropic
embryotic
blockable
excusable
rejudging
audiobook
proofroom
quercetin
opacifier
labellers
garroters
housesits
adjutants
supremely
#+END_SRC

* Create Leading Zeros

Create leading zeros only for id columns. Please use generic approach!
** Start file
#+BEGIN_SRC 
id      data    age     parent_id
11      "Test"  12      123
123     "Test2  11      null
155     "Test5  19      123
111     "Test"  12      1123
1123    "Test2  11      11
1155    "Test5  19      1123
211     "Test"  12      123
2123    "Test2  11      11
2155    "Test5  19      123
2111    "Test"  12      1123
3123    "Test2  11      11
3155    "Test5  19      1123
1       "root"  9       null
#+END_SRC

** End file
#+BEGIN_SRC 
id      data    age     parent_id
0011    "Test"  12      0123
0123    "Test2  11      null
0155    "Test5  19      0123
0111    "Test"  12      1123
1123    "Test2  11      0011
1155    "Test5  19      1123
0211    "Test"  12      0123
2123    "Test2  11      0011
2155    "Test5  19      0123
2111    "Test"  12      1123
3123    "Test2  11      0011
3155    "Test5  19      1123
0001    "root"  9       null
#+END_SRC

* Enumerate words

Enumerate the unique words in order.
** Start file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet.
#+END_SRC

** End file
#+BEGIN_SRC 
Accusam
Aliquyam
Amet
At
Clita
Consetetur
Diam
Dolor
Dolore
Dolores
Duo
Ea
Eirmod
Elitr
Eos
Erat
Est
Et
Gubergren
Invidunt
Ipsum
Justo
Kasd
Labore
Lorem
Magna
No
Nonumy
Rebum
Sadipscing
Sanctus
Sea
Sed
Sit
Stet
Takimata
Tempor
Ut
Vero
Voluptua
#+END_SRC

* Number an outline

The indent and words are right, but the numbers are all wrong.
** Start file
#+BEGIN_SRC 
1. One
  1. One
    1. One
  1. Two
    1. One
    1. Two
      1. One
    1. Three
    1. Four
  1. Three
    1. One
      1. One
      1. Two
    1. Two
  1. Four
    1. One
    1. Two
    1. Three
    1. Four
    1. Five
    1. Six
  1. Five
    1. One
    1. Two
    1. Three
1. Two
  1. One
    1. One
    1. Two
    1. Three
    1. Four
    1. Five
  1. Two
#+END_SRC

** End file
#+BEGIN_SRC 
1. One
  1. One
    1. One
  2. Two
    1. One
    2. Two
      1. One
    3. Three
    4. Four
  3. Three
    1. One
      1. One
      2. Two
    2. Two
  4. Four
    1. One
    2. Two
    3. Three
    4. Four
    5. Five
    6. Six
  5. Five
    1. One
    2. Two
    3. Three
2. Two
  1. One
    1. One
    2. Two
    3. Three
    4. Four
    5. Five
  2. Two
#+END_SRC

* create arrows in a list

Add arrow at same distance
** Start file
#+BEGIN_SRC 
milk
coffe
toothpaste
potatoes
tomatoes
nuts
tuna cans
#+END_SRC

** End file
#+BEGIN_SRC 
milk       -->
coffe      -->
toothpaste -->
potatoes   -->
tomatoes   -->
nuts       -->
tuna cans  -->
#+END_SRC

* Compile C

You might have to get clever to do this one.
** Start file
#+BEGIN_SRC 
int main()
{
  char *s = "Hello, world!";
  int i, j;

  for (i = 0; s[i]; i++) {
    for (j = 0; j <= i; j++)
      putchar(s[j]);
    putchar('\n');
  }

  return 0;
}
#+END_SRC

** End file
#+BEGIN_SRC 
H
He
Hel
Hell
Hello
Hello,
Hello, 
Hello, w
Hello, wo
Hello, wor
Hello, worl
Hello, world
Hello, world!
#+END_SRC

* Alphabetize the directory

Put the contacts and their information in alphabetical order.
** Start file
#+BEGIN_SRC 
## Directory
   * Smith, George
      - 1234 Avenue, New York, NY
   * Bailey, Stephen
      - 4545 Harbor Ln, Atlanta, GA
      - Phone: (412) 291-1238
   * Thomas, Brent
      - 1482 Mystic Oaks, Anaheim, CA
   * Grant, Jenny
      - 198 Circle Dr, Houston, TX
      - Phone: (213) 198-9842
      - Email: jenny.grant@gmail.com
   * Percy, Adam
      - 221 Jaguar Pkwy, Missoula, MT
   * Garfield, Misty
      - 5988 Apple Tree Ln, Memphis, TN
   * Parsons, Betty
      - Phone: (235) 523-2378
      - Email: bettyboop123@gmail.com
   * Sanders, Terry
      - Email: sanderst@yahoo.com
   * Smith, Pete
      - Phone: (294) 984-2938
   * Frost, Jennifer
      - 2498 Temple Terrace, Miami, FL
   * Matthews, Frank
      - 418 Happy Trail, Phoenix, AZ
      - Phone: (985) 129-2394
      - Email: frank@phoenixrealtors.net
   * Allen, Taylor
      - Email: allen.taylor@hotmail.com
   * McCullen, Sarah
      - 247 Hidden Elm, Seattle, WA
      - Phone: (288) 283-4568
   * Perkins, Mike
      - 992 Peartree Ln, Bowling Green, KY
#+END_SRC

** End file
#+BEGIN_SRC 
## Directory
   #+END_SRC

* Allen, Taylor
      - Email: allen.taylor@hotmail.com
   * Bailey, Stephen
      - 4545 Harbor Ln, Atlanta, GA
      - Phone: (412) 291-1238
   * Frost, Jennifer
      - 2498 Temple Terrace, Miami, FL
   * Garfield, Misty
      - 5988 Apple Tree Ln, Memphis, TN
   * Grant, Jenny
      - 198 Circle Dr, Houston, TX
      - Phone: (213) 198-9842
      - Email: jenny.grant@gmail.com
   * Matthews, Frank
      - 418 Happy Trail, Phoenix, AZ
      - Phone: (985) 129-2394
      - Email: frank@phoenixrealtors.net
   * McCullen, Sarah
      - 247 Hidden Elm, Seattle, WA
      - Phone: (288) 283-4568
   * Parsons, Betty
      - Phone: (235) 523-2378
      - Email: bettyboop123@gmail.com
   * Percy, Adam
      - 221 Jaguar Pkwy, Missoula, MT
   * Perkins, Mike
      - 992 Peartree Ln, Bowling Green, KY
   * Sanders, Terry
      - Email: sanderst@yahoo.com
   * Smith, George
      - 1234 Avenue, New York, NY
   * Smith, Pete
      - Phone: (294) 984-2938
   * Thomas, Brent
      - 1482 Mystic Oaks, Anaheim, CA

* Deleting folded text

The text below contains three folds. Delete them (and the text inside them). For example: 123 456 /*{{{*/ 789 /*}}}*/ 012 Should become: 123 012 Also, add `aoeuaoeu` to make sure small solutions don't get flagged as cheating.
** Start file
#+BEGIN_SRC 
/* vim: set foldmethod=marker: */
679
196
273
094
912
132
235
859
303
989
151
012
912
279
955
000
333
383
863
009
203
382
388
506
125
858
364
344
927
961
215
856
007
116
412
535
923
656
658
396
045
800
830
923
901
571
003
296
513
721
435
617
738
332
267
987
113
415
773
460
455
737
745
510
047
010
501
617
594
867
834
722
605
348
486
862
570
026
157
127
378
291
066
228
968
296
212
522
017
345
885
628
801
417
734
934
848
973
001
678
225
941
615
340
673
549
068
083
294
271
760
992
777
005
892
373
938
976
648
140
810
135
150
705
021
318
441
983
080
699
378
886
193
510
386
113
194
168
837
823
282
394
888
896
960
728
385
094
656
275
266
311
406
944
201
663
027
534
565
260
971
794
268
602
789
651
487
906
602
945
965
951
616
211
543
068
703
580
064
164
801
228
183
672
285
985
845
567
922
232
022
889
627
146
941
097
929
936
911
178
580  /*{{{*/
667
551
619
719
760
854
627
603
912
055
167
988
543
241
573
782
201
707
427
871
614
956
300
967
473
824
512
110
161
923
293
846
926
414
478
459
927
511
689
592
062
884
260
138
314
591
968
607
877
764
890
634
920
385
645
744
843
309
178
842
645
930
215
531
935
932
705
952
151
970
931
854
209
754
315
223
243
452
165
809
225
599
979
290
108
323
476
597
613
758
186
401
283
556
234
027
105
848
478
811  /*}}}*/
575
959
081
667
261
988
881
161
932
304
739
371
554
195
187
378
424
479
869
488
956
249
039
111
535
822
358
419
730
126
528
846
209
438
190
643
496
252
468
152
799
308
092
924
528
551
637
108
632
010
676
680
249
435
930
957
066
599
124
501
706
849
733
220
205
355
157
389
989
250
496
935
241
835
416
321
898
866
293
018
892
946
387
827
331
435
330
431
776
130
416
216
219
240
507
790
869
975
651
785
806  /*{{{*/
709
177
827
087
863
585
837
447
728
459
256
899
900
047
117
260
229
847
954
271
903
765
802
596
315
583
590
363
576
630
292
383
163
420
183
359
961
051
325
823
024
951
050
074
423
915
744
747
817
388
882
207
202
188
614
451
991
328
397
059
564
150
076
962
528
455
151
113
064
064
154
313
924
759
688
526
591
349
019
710
119
417
009
534
652
469
133
698
266
290
482
023
285
648
266
139
408
041
169
104  /*}}}*/
545
215
439
434
171
376
297
049
857
922
573
422
193
186
922
089
825
159
364
168
444
989
947
096
393
938
195
127
411
905
501
686
391
181
121
714
084
942
212
720
265
895
328
793
276
118
841
297
543
276
246
946
154
842
932
054
137
562
804
165
273
112
019
658
652
696
870
514
997
721
995
141
619
722
440
167
163
339
953
043
032
880
636
223
460
808
929
215
136
121
793
460
186
193
377
842
952
994
394
453
299  /*{{{*/
036
497
877
169
865
288
216
299
950
048
595
421
568
574
188
049
480
575
990
301
616
716
483
333
870
584
544
726
483
918
730
800
078
978
537
737
194
737
995
402
875
048
948
641
931
309
921
901
611
867
506
362
534
570
724
025
482
145
058
436
917
382
261
464
104
432
063
799
057
482
518
451
236
861
902
989
476
807
993
318
448
240
476
409
262
469
404
104
353
798
829
258
349
016
567
552
395
264
927
433  /*}}}*/
335
404
930
040
610
297
463
393
557
523
216
689
608
153
776
163
396
618
027
469
052
291
867
705
512
104
181
741
195
416
149
535
321
543
521
827
659
169
883
621
274
914
961
887
266
431
589
383
647
414
196
224
506
609
566
396
846
808
112
483
972
083
420
253
745
450
727
973
765
892
391
214
244
671
177
210
414
618
491
104
604
252
967
080
649
019
410
143
312
529
903
723
738
449
955
387
906
079
506
584
#+END_SRC

** End file
#+BEGIN_SRC 
/#+END_SRC

* vim: set foldmethod=marker: */
aoeuaoeu
679
196
273
094
912
132
235
859
303
989
151
012
912
279
955
000
333
383
863
009
203
382
388
506
125
858
364
344
927
961
215
856
007
116
412
535
923
656
658
396
045
800
830
923
901
571
003
296
513
721
435
617
738
332
267
987
113
415
773
460
455
737
745
510
047
010
501
617
594
867
834
722
605
348
486
862
570
026
157
127
378
291
066
228
968
296
212
522
017
345
885
628
801
417
734
934
848
973
001
678
225
941
615
340
673
549
068
083
294
271
760
992
777
005
892
373
938
976
648
140
810
135
150
705
021
318
441
983
080
699
378
886
193
510
386
113
194
168
837
823
282
394
888
896
960
728
385
094
656
275
266
311
406
944
201
663
027
534
565
260
971
794
268
602
789
651
487
906
602
945
965
951
616
211
543
068
703
580
064
164
801
228
183
672
285
985
845
567
922
232
022
889
627
146
941
097
929
936
911
178
575
959
081
667
261
988
881
161
932
304
739
371
554
195
187
378
424
479
869
488
956
249
039
111
535
822
358
419
730
126
528
846
209
438
190
643
496
252
468
152
799
308
092
924
528
551
637
108
632
010
676
680
249
435
930
957
066
599
124
501
706
849
733
220
205
355
157
389
989
250
496
935
241
835
416
321
898
866
293
018
892
946
387
827
331
435
330
431
776
130
416
216
219
240
507
790
869
975
651
785
545
215
439
434
171
376
297
049
857
922
573
422
193
186
922
089
825
159
364
168
444
989
947
096
393
938
195
127
411
905
501
686
391
181
121
714
084
942
212
720
265
895
328
793
276
118
841
297
543
276
246
946
154
842
932
054
137
562
804
165
273
112
019
658
652
696
870
514
997
721
995
141
619
722
440
167
163
339
953
043
032
880
636
223
460
808
929
215
136
121
793
460
186
193
377
842
952
994
394
453
335
404
930
040
610
297
463
393
557
523
216
689
608
153
776
163
396
618
027
469
052
291
867
705
512
104
181
741
195
416
149
535
321
543
521
827
659
169
883
621
274
914
961
887
266
431
589
383
647
414
196
224
506
609
566
396
846
808
112
483
972
083
420
253
745
450
727
973
765
892
391
214
244
671
177
210
414
618
491
104
604
252
967
080
649
019
410
143
312
529
903
723
738
449
955
387
906
079
506
584

* Extract HTML option values from tag values

Generate HTML option values from the text in the option tag. If the text contains multiple words, replace the spaces with an underscore and convert all capital letters to small letters.
** Start file
#+BEGIN_SRC 
<select>
  <option>Volvo</option>
  <option>Aston Martin</option>
  <option>Audi</option>
  <option>Alfa Romeo</option>
</select>
#+END_SRC

** End file
#+BEGIN_SRC 
<select>
  <option value="volvo">Volvo</option>
  <option value="aston_martin">Aston Martin</option>
  <option value="audi">Audi</option>
  <option value="alfa_romeo">Alfa Romeo</option>
</select>
#+END_SRC

* increment by column in XML

modify an arbitrary "column" in an xml table by incrementing a an arbitrary placeholder string
** Start file
#+BEGIN_SRC 
<root>
  <row>
    <alpha>mail</alpha>
    <bravo>@@@@@</bravo>
  </row>
  <row>
    <alpha>male</alpha>
    <bravo>@@@@@</bravo>
  </row>
  <row>
    <alpha>mayel</alpha>
    <bravo>@@@@@</bravo>
  </row>
  <row>
    <alpha>mahel</alpha>
    <bravo>@@@@@</bravo>
  </row>
</root>
#+END_SRC

** End file
#+BEGIN_SRC 
<root>
  <row>
    <alpha>mail</alpha>
    <bravo>10000</bravo>
  </row>
  <row>
    <alpha>male</alpha>
    <bravo>10001</bravo>
  </row>
  <row>
    <alpha>mayel</alpha>
    <bravo>10002</bravo>
  </row>
  <row>
    <alpha>mahel</alpha>
    <bravo>10003</bravo>
  </row>
</root>
#+END_SRC

* Sorting a glossary

Sort a glossary. Glossary head contains a header phrase ending with ':' and glossary body has multi line text indented with a tab.
** Start file
#+BEGIN_SRC 
zomg:
    Multiline description
    about zomg.

abc:
    Multiline description
    about abc.
#+END_SRC

** End file
#+BEGIN_SRC 
abc:
    Multiline description
    about abc.

zomg:
    Multiline description
    about zomg.
#+END_SRC

* Prime Numbers

List the first 100 prime numbers.
** Start file
#+BEGIN_SRC 
Prime Numbers
#+END_SRC

** End file
#+BEGIN_SRC 
2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89
97
101
103
107
109
113
127
131
137
139
149
151
157
163
167
173
179
181
191
193
197
199
211
223
227
229
233
239
241
251
257
263
269
271
277
281
283
293
307
311
313
317
331
337
347
349
353
359
367
373
379
383
389
397
401
409
419
421
431
433
439
443
449
457
461
463
467
479
487
491
499
503
509
521
523
541
#+END_SRC

* Word frequency alignment

You've got to align the second column, but the spacing is inconvenient and there are nasty tabs in the way. If you're a "real Vim ninja," this could be very quick indeed...
** Start file
#+BEGIN_SRC 
     align here
the        56271872
of        33950064
and        29944184
to        25956096
in        17420636
I        11764797
that        11073318
was        10078245
his        8799755
he        8397205
it        8058110
#+END_SRC

** End file
#+BEGIN_SRC 
     align here
the  56271872
of   33950064
and  29944184
to   25956096
in   17420636
I    11764797
that 11073318
was  10078245
his  8799755
he   8397205
it   8058110
#+END_SRC

* Subtraction

Solve the equations.
** Start file
#+BEGIN_SRC 
xx - x =
xxx - x =
xxxx - x =
xxxxx - x =
xxxxx - xx =
xxxxxx - xxxxx =
xxxxxxx - xx =
xxxxxxx - xx =
xxxxxxxx - xx =
xxxxxxxx - xxxxx =
xxxxxxxx - xxxxxx =
xxxxxxxxx - xxx =
xxxxxxxxxx - xxxxx =
xxxxxxxxxx - xxxxxxxx =
xxxxxxxxxxx - xxxx =
xxxxxxxxxxx - xxxxx =
xxxxxxxxxxxxx - xxxxxx =
xxxxxxxxxxxxxx - xxx =
xxxxxxxxxxxxxxx - xx =
xxxxxxxxxxxxxxxx - xxxxxxxx =
#+END_SRC

** End file
#+BEGIN_SRC 
xx - x = x
xxx - x = xx
xxxx - x = xxx
xxxxx - x = xxxx
xxxxx - xx = xxx
xxxxxx - xxxxx = x
xxxxxxx - xx = xxxxx
xxxxxxx - xx = xxxxx
xxxxxxxx - xx = xxxxxx
xxxxxxxx - xxxxx = xxx
xxxxxxxx - xxxxxx = xx
xxxxxxxxx - xxx = xxxxxx
xxxxxxxxxx - xxxxx = xxxxx
xxxxxxxxxx - xxxxxxxx = xx
xxxxxxxxxxx - xxxx = xxxxxxx
xxxxxxxxxxx - xxxxx = xxxxxx
xxxxxxxxxxxxx - xxxxxx = xxxxxxx
xxxxxxxxxxxxxx - xxx = xxxxxxxxxxx
xxxxxxxxxxxxxxx - xx = xxxxxxxxxxxxx
xxxxxxxxxxxxxxxx - xxxxxxxx = xxxxxxxx
#+END_SRC

* Format java properties

Format java properties to a different format. The value which is the string following the first '=' cannot & should not change. All periods in the key get replaced with an underscore "_" and get a prefix of "b_".
** Start file
#+BEGIN_SRC 
# Set a.b
a.b=123
x.y.z=xyz.def
tini=00.x
# Change url to qa
url=http://aabb.com/cache=true
debug.java-options=-Xmx2g
a.b.c.d.e=twenty
#+END_SRC

** End file
#+BEGIN_SRC 
# Set a.b
b_a_b=123
b_x_y_z=xyz.def
b_tini=00.x
# Change url to qa
b_url=http://aabb.com/cache=true
b_debug_java-options=-Xmx2g
b_a_b_c_d_e=twenty
#+END_SRC

* Top X

The End File is the Top 10 Vimgolf Leaderboard at June 29, 2013. This is a second version, with a great contribution of @udioica. X is ten in Roman,a numeric system in ancient Rome
** Start file
#+BEGIN_SRC 
udioica udioica gumnos gumnos wondible wondible h_east h_east gumnos KersonHsiao h_east federicogalassi federicogalassi gumnos connermcd connermcd federicogalassi h_east clvv42 clvv42 wondible DoomedBunnies DoomedBunnies clvv42 udioica connermcd _mhinz_ _mhinz_ DoomedBunnies
#+END_SRC

** End file
#+BEGIN_SRC 
udioica gumnos wondible h_east KersonHsiao federicogalassi connermcd clvv42 DoomedBunnies _mhinz_
#+END_SRC
* Interleave lines

This is some kind of « paste -d'\n' c b a ». There are many ways to achieve this.. just find the shortest!
** Start file

#+BEGIN_SRC 
kif_004c.jpg
p1000055.jpg
mov00843.mpg
dsc00959.jpg

1978-07-29
2004-08-22
2007-01-18
2015-03-15

OVEGU
FXNGR
QNAPR
GBQNL
#+END_SRC

** End file

#+BEGIN_SRC 
OVEGU
1978-07-29
kif_004c.jpg
FXNGR
2004-08-22
p1000055.jpg
QNAPR
2007-01-18
mov00843.mpg
GBQNL
2015-03-15
dsc00959.jpg
#+END_SRC
 
* Change name of a variable

Replace the name of the $variable with the fastest move possible. The challenge is having a command that allow you to easily change the variable name even if its indented.
** Start file

#+BEGIN_SRC 
var $oki = "value";
#+END_SRC

** End file

#+BEGIN_SRC 
var $hl = "value";
#+END_SRC

* Fix the Haiku

Change this slightly scrambled haiku to its unscrambled form and fix the capitalisation and punctuation along the way.
** Start file
#+BEGIN_SRC 
at over-matured the sushi
master the
is of full regret
#+END_SRC

** End file

#+BEGIN_SRC 
    At the over-matured sushi,
    The Master
    Is full of regret.
#+END_SRC

* 82 bottles of beer on the wall

Take them down. (sorry, only 82 bottles because the problem size is limited!)
** Start file

#+BEGIN_SRC 
82 bottles of beer on the wall, 82 bottles of beer.
#+END_SRC

** End file

#+BEGIN_SRC 
82 bottles of beer on the wall, 82 bottles of beer.
Take one down and pass it around, 81 bottles of beer on the wall.

81 bottles of beer on the wall, 81 bottles of beer.
Take one down and pass it around, 80 bottles of beer on the wall.

80 bottles of beer on the wall, 80 bottles of beer.
Take one down and pass it around, 79 bottles of beer on the wall.

79 bottles of beer on the wall, 79 bottles of beer.
Take one down and pass it around, 78 bottles of beer on the wall.

78 bottles of beer on the wall, 78 bottles of beer.
Take one down and pass it around, 77 bottles of beer on the wall.

77 bottles of beer on the wall, 77 bottles of beer.
Take one down and pass it around, 76 bottles of beer on the wall.

76 bottles of beer on the wall, 76 bottles of beer.
Take one down and pass it around, 75 bottles of beer on the wall.

75 bottles of beer on the wall, 75 bottles of beer.
Take one down and pass it around, 74 bottles of beer on the wall.

74 bottles of beer on the wall, 74 bottles of beer.
Take one down and pass it around, 73 bottles of beer on the wall.

73 bottles of beer on the wall, 73 bottles of beer.
Take one down and pass it around, 72 bottles of beer on the wall.

72 bottles of beer on the wall, 72 bottles of beer.
Take one down and pass it around, 71 bottles of beer on the wall.

71 bottles of beer on the wall, 71 bottles of beer.
Take one down and pass it around, 70 bottles of beer on the wall.

70 bottles of beer on the wall, 70 bottles of beer.
Take one down and pass it around, 69 bottles of beer on the wall.

69 bottles of beer on the wall, 69 bottles of beer.
Take one down and pass it around, 68 bottles of beer on the wall.

68 bottles of beer on the wall, 68 bottles of beer.
Take one down and pass it around, 67 bottles of beer on the wall.

67 bottles of beer on the wall, 67 bottles of beer.
Take one down and pass it around, 66 bottles of beer on the wall.

66 bottles of beer on the wall, 66 bottles of beer.
Take one down and pass it around, 65 bottles of beer on the wall.

65 bottles of beer on the wall, 65 bottles of beer.
Take one down and pass it around, 64 bottles of beer on the wall.

64 bottles of beer on the wall, 64 bottles of beer.
Take one down and pass it around, 63 bottles of beer on the wall.

63 bottles of beer on the wall, 63 bottles of beer.
Take one down and pass it around, 62 bottles of beer on the wall.

62 bottles of beer on the wall, 62 bottles of beer.
Take one down and pass it around, 61 bottles of beer on the wall.

61 bottles of beer on the wall, 61 bottles of beer.
Take one down and pass it around, 60 bottles of beer on the wall.

60 bottles of beer on the wall, 60 bottles of beer.
Take one down and pass it around, 59 bottles of beer on the wall.

59 bottles of beer on the wall, 59 bottles of beer.
Take one down and pass it around, 58 bottles of beer on the wall.

58 bottles of beer on the wall, 58 bottles of beer.
Take one down and pass it around, 57 bottles of beer on the wall.

57 bottles of beer on the wall, 57 bottles of beer.
Take one down and pass it around, 56 bottles of beer on the wall.

56 bottles of beer on the wall, 56 bottles of beer.
Take one down and pass it around, 55 bottles of beer on the wall.

55 bottles of beer on the wall, 55 bottles of beer.
Take one down and pass it around, 54 bottles of beer on the wall.

54 bottles of beer on the wall, 54 bottles of beer.
Take one down and pass it around, 53 bottles of beer on the wall.

53 bottles of beer on the wall, 53 bottles of beer.
Take one down and pass it around, 52 bottles of beer on the wall.

52 bottles of beer on the wall, 52 bottles of beer.
Take one down and pass it around, 51 bottles of beer on the wall.

51 bottles of beer on the wall, 51 bottles of beer.
Take one down and pass it around, 50 bottles of beer on the wall.

50 bottles of beer on the wall, 50 bottles of beer.
Take one down and pass it around, 49 bottles of beer on the wall.

49 bottles of beer on the wall, 49 bottles of beer.
Take one down and pass it around, 48 bottles of beer on the wall.

48 bottles of beer on the wall, 48 bottles of beer.
Take one down and pass it around, 47 bottles of beer on the wall.

47 bottles of beer on the wall, 47 bottles of beer.
Take one down and pass it around, 46 bottles of beer on the wall.

46 bottles of beer on the wall, 46 bottles of beer.
Take one down and pass it around, 45 bottles of beer on the wall.

45 bottles of beer on the wall, 45 bottles of beer.
Take one down and pass it around, 44 bottles of beer on the wall.

44 bottles of beer on the wall, 44 bottles of beer.
Take one down and pass it around, 43 bottles of beer on the wall.

43 bottles of beer on the wall, 43 bottles of beer.
Take one down and pass it around, 42 bottles of beer on the wall.

42 bottles of beer on the wall, 42 bottles of beer.
Take one down and pass it around, 41 bottles of beer on the wall.

41 bottles of beer on the wall, 41 bottles of beer.
Take one down and pass it around, 40 bottles of beer on the wall.

40 bottles of beer on the wall, 40 bottles of beer.
Take one down and pass it around, 39 bottles of beer on the wall.

39 bottles of beer on the wall, 39 bottles of beer.
Take one down and pass it around, 38 bottles of beer on the wall.

38 bottles of beer on the wall, 38 bottles of beer.
Take one down and pass it around, 37 bottles of beer on the wall.

37 bottles of beer on the wall, 37 bottles of beer.
Take one down and pass it around, 36 bottles of beer on the wall.

36 bottles of beer on the wall, 36 bottles of beer.
Take one down and pass it around, 35 bottles of beer on the wall.

35 bottles of beer on the wall, 35 bottles of beer.
Take one down and pass it around, 34 bottles of beer on the wall.

34 bottles of beer on the wall, 34 bottles of beer.
Take one down and pass it around, 33 bottles of beer on the wall.

33 bottles of beer on the wall, 33 bottles of beer.
Take one down and pass it around, 32 bottles of beer on the wall.

32 bottles of beer on the wall, 32 bottles of beer.
Take one down and pass it around, 31 bottles of beer on the wall.

31 bottles of beer on the wall, 31 bottles of beer.
Take one down and pass it around, 30 bottles of beer on the wall.

30 bottles of beer on the wall, 30 bottles of beer.
Take one down and pass it around, 29 bottles of beer on the wall.

29 bottles of beer on the wall, 29 bottles of beer.
Take one down and pass it around, 28 bottles of beer on the wall.

28 bottles of beer on the wall, 28 bottles of beer.
Take one down and pass it around, 27 bottles of beer on the wall.

27 bottles of beer on the wall, 27 bottles of beer.
Take one down and pass it around, 26 bottles of beer on the wall.

26 bottles of beer on the wall, 26 bottles of beer.
Take one down and pass it around, 25 bottles of beer on the wall.

25 bottles of beer on the wall, 25 bottles of beer.
Take one down and pass it around, 24 bottles of beer on the wall.

24 bottles of beer on the wall, 24 bottles of beer.
Take one down and pass it around, 23 bottles of beer on the wall.

23 bottles of beer on the wall, 23 bottles of beer.
Take one down and pass it around, 22 bottles of beer on the wall.

22 bottles of beer on the wall, 22 bottles of beer.
Take one down and pass it around, 21 bottles of beer on the wall.

21 bottles of beer on the wall, 21 bottles of beer.
Take one down and pass it around, 20 bottles of beer on the wall.

20 bottles of beer on the wall, 20 bottles of beer.
Take one down and pass it around, 19 bottles of beer on the wall.

19 bottles of beer on the wall, 19 bottles of beer.
Take one down and pass it around, 18 bottles of beer on the wall.

18 bottles of beer on the wall, 18 bottles of beer.
Take one down and pass it around, 17 bottles of beer on the wall.

17 bottles of beer on the wall, 17 bottles of beer.
Take one down and pass it around, 16 bottles of beer on the wall.

16 bottles of beer on the wall, 16 bottles of beer.
Take one down and pass it around, 15 bottles of beer on the wall.

15 bottles of beer on the wall, 15 bottles of beer.
Take one down and pass it around, 14 bottles of beer on the wall.

14 bottles of beer on the wall, 14 bottles of beer.
Take one down and pass it around, 13 bottles of beer on the wall.

13 bottles of beer on the wall, 13 bottles of beer.
Take one down and pass it around, 12 bottles of beer on the wall.

12 bottles of beer on the wall, 12 bottles of beer.
Take one down and pass it around, 11 bottles of beer on the wall.

11 bottles of beer on the wall, 11 bottles of beer.
Take one down and pass it around, 10 bottles of beer on the wall.

10 bottles of beer on the wall, 10 bottles of beer.
Take one down and pass it around, 9 bottles of beer on the wall.

9 bottles of beer on the wall, 9 bottles of beer.
Take one down and pass it around, 8 bottles of beer on the wall.

8 bottles of beer on the wall, 8 bottles of beer.
Take one down and pass it around, 7 bottles of beer on the wall.

7 bottles of beer on the wall, 7 bottles of beer.
Take one down and pass it around, 6 bottles of beer on the wall.

6 bottles of beer on the wall, 6 bottles of beer.
Take one down and pass it around, 5 bottles of beer on the wall.

5 bottles of beer on the wall, 5 bottles of beer.
Take one down and pass it around, 4 bottles of beer on the wall.

4 bottles of beer on the wall, 4 bottles of beer.
Take one down and pass it around, 3 bottles of beer on the wall.

3 bottles of beer on the wall, 3 bottles of beer.
Take one down and pass it around, 2 bottles of beer on the wall.

2 bottles of beer on the wall, 2 bottles of beer.
Take one down and pass it around, 1 bottle of beer on the wall.

1 bottle of beer on the wall, 1 bottle of beer.
Go to the store and buy some more, 99 bottles of beer on the wall.
#+END_SRC

* expand a list comprehension (python)

Please show your way to convert a list comprehension in python to an ordinary for-loop expression!
** Start file

#+BEGIN_SRC 
print [x**2 for x in xrange(10)]
#+END_SRC

** End file

#+BEGIN_SRC 
tmp = []
for x in xrange(10):
    tmp.append(x**2)
print tmp
#+END_SRC

* Pretty format for variable declarations

Project standards demand the equal signs must be aligned for better readability.
** Start file

#+BEGIN_SRC 
var parser = require('../src/grammar.js'),
    src = require('../src/blueberry.js'),
    fs = require('fs'),
    glob = require('glob');
#+END_SRC

** End file

#+BEGIN_SRC 
var parser = require('../src/grammar.js'),
    src    = require('../src/blueberry.js'),
    fs     = require('fs'),
    glob   = require('glob');
#+END_SRC

* Round Round

Round Round
** Start file

#+BEGIN_SRC 
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
RRRRRRRRRRRRRRR
#+END_SRC

** End file

#+BEGIN_SRC 
RrRRRRRRRRRRRRR
RrRrrrrrrrrrrrR
RrRrRRRRRRRRRrR
RrRrRrrrrrrrRrR
RrRrRrRRRRRrRrR
RrRrRrRrrrRrRrR
RrRrRrRrRrRrRrR
RrRrRrRrRrRrRrR
RrRrRrRrRrRrRrR
RrRrRrRrRrRrRrR
RrRrRrRRRrRrRrR
RrRrRrrrrrRrRrR
RrRrRRRRRRRrRrR
RrRrrrrrrrrrRrR
RrRRRRRRRRRRRrR
RrrrrrrrrrrrrrR
RRRRRRRRRRRRRRR
#+END_SRC

* Python to Ruby

Convert this Python code to Ruby. NOTE: This program likely won't run.

** Start file

#+BEGIN_SRC 
class PythonToRuby:
  def add(x, y):
    x + y

  n = add(1 + 1)
#+END_SRC

** End file

#+BEGIN_SRC 
class PythonToRuby
        def add(x, y)
                x + y
        end

        n = add(1, 2)
end
#+END_SRC

* Recursively Palindrome

Note that there are 2^6-1 characters.
** Start file

#+BEGIN_SRC 
6
#+END_SRC

** End file

#+BEGIN_SRC 
abacabadabacabaeabacabadabacabafabacabadabacabaeabacabadabacaba
#+END_SRC

* Cleanining up 80 column concatenated text

1. Put the whole query on one line, remove the concatenation operators 2. Remove the double spaces that appear a few times in the query 3. Use string-interpolated variable statementPid rather than the ugly concatenation

** Start file

#+BEGIN_SRC 
$atres = sqlStatement("select f.name,f.street,f.city,f.state,f.postal_code from facility f " .
  " left join users u on f.id=u.facility_id " .
  " left join  billing b on b.provider_id=u.id and b.pid = '".$stmt['pid']."' " .
  " where  service_location=1");
$row = sqlFetchArray($atres);
#+END_SRC

** End file

#+BEGIN_SRC 
$atres = sqlStatement("select f.name,f.street,f.city,f.state,f.postal_code from facility f left join users u on f.id=u.facility_id left join billing b on b.provider_id=u.id and b.pid = $statementPid where service_location=1");
$row = sqlFetchArray($atres);
#+END_SRC

* Manual SQL

Change select and insert queries to simulate inserting a new record.

** Start file

#+BEGIN_SRC 
select * from service where user_id = '908' and service_id = (233);
select * from discounts where user_id = '908';

insert into discounts values (null, 0, 908, 1, 233, 'STI-0128862-3', '2015-11-20', '2017-11-20', 0, 900, null, now());
#+END_SRC

** End file

#+BEGIN_SRC 
select * from service where user_id = '909' and service_id = (322);
select * from discounts where user_id = '909';

insert into discounts values (null, 0, 909, 2, 322, 'STI-0132580-2', '2015-11-01', '2018-10-01', 0, 136.8, null, now());
#+END_SRC

* Parsing with CSV: Unify lines and result.

col1;col2;col3;col4 A;1;4;5 A;3;4; A;1;4; # New output: col1;col2;col3;col4 A;1(2x);3;4(3x);5 any ideas?

** Start file

#+BEGIN_SRC 
col1;col2;col3;col4
A;1;4;5
A;3;4;
A;1;4;
#+END_SRC

** End file

#+BEGIN_SRC 
col1;col2;col3;col4
A;1(2x);3;4(3x);5
#+END_SRC

* Sort the cardinal numbers

Maybe a simple challenge.

** Start file

#+BEGIN_SRC 
Zero
One
Two
Three
Four
Five
Six
Seventeen
Sixteen
Fifteen
Fourteen
Thirteen
Twelve
Eleven
Ten
Nine
Eight
Seven
Eighteen
Nineteen
Twenty
Twenty-one
#+END_SRC

** End file

#+BEGIN_SRC 
Zero
One
Two
Three
Four
Five
Six
Seven
Eight
Nine
Ten
Eleven
Twelve
Thirteen
Fourteen
Fifteen
Sixteen
Seventeen
Eighteen
Nineteen
Twenty
Twenty-one
#+END_SRC

* Java Array2List

Convert an java array initializer into a list.
** Start file

#+BEGIN_SRC 
double[] c = 
{
        112.2, 102, 12, 954, 39.43,
        49.4, 2224.6, 94, 123,
        4929.55, 12, 98, 91.22
};
#+END_SRC

** End file

#+BEGIN_SRC 
List<Double> c = new ArrayList<Double>();
c.add(112.2);
c.add(102d);
c.add(12d);
c.add(954d);
c.add(39.43);
c.add(49.4);
c.add(2224.6);
c.add(94d);
c.add(123d);
c.add(4929.55);
c.add(12d);
c.add(98d);
c.add(91.22);
#+END_SRC

* Back to the roots

Johnny has a file with more integers. He wants to change each number with its square root. Can you help him?

** Start file

#+BEGIN_SRC 
13
81
1024
72
144
51
90
2
77
25
625
4
#+END_SRC

** End file

#+BEGIN_SRC 
3.605551
9.0
32.0
8.485281
12.0
7.141428
9.486833
1.414214
8.774964
5.0
25.0
2.0
#+END_SRC

* Test everything!

... and build the desired input data structure. Transform a list of values into a non-trivial format.
** Start file

#+BEGIN_SRC 
        { changed_field => 'lorem', old_value => 'a', new_value => 'b' },
lorem ipsum dolor sit amet elitr sed diam non umy eir mod tempor invi dunt lab ore
dol1 dol2 dol3 dol4 dol5 dol6 dol7 dol8 dol9 dol10 mag1 mag2 mag3 mag4 mag5 mag6 mag7 mag8 mag9 mag10
#+END_SRC

** End file

#+BEGIN_SRC 
        { changed_field => 'lorem', old_value => 'a', new_value => 'b' },
        { changed_field => 'ipsum', old_value => 'a', new_value => 'b' },
        { changed_field => 'dolor', old_value => 'a', new_value => 'b' },
        { changed_field => 'sit', old_value => 'a', new_value => 'b' },
        { changed_field => 'amet', old_value => 'a', new_value => 'b' },
        { changed_field => 'elitr', old_value => 'a', new_value => 'b' },
        { changed_field => 'sed', old_value => 'a', new_value => 'b' },
        { changed_field => 'diam', old_value => 'a', new_value => 'b' },
        { changed_field => 'non', old_value => 'a', new_value => 'b' },
        { changed_field => 'umy', old_value => 'a', new_value => 'b' },
        { changed_field => 'eir', old_value => 'a', new_value => 'b' },
        { changed_field => 'mod', old_value => 'a', new_value => 'b' },
        { changed_field => 'tempor', old_value => 'a', new_value => 'b' },
        { changed_field => 'invi', old_value => 'a', new_value => 'b' },
        { changed_field => 'dunt', old_value => 'a', new_value => 'b' },
        { changed_field => 'lab', old_value => 'a', new_value => 'b' },
        { changed_field => 'ore', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol1', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol2', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol3', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol4', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol5', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol6', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol7', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol8', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol9', old_value => 'a', new_value => 'b' },
        { changed_field => 'dol10', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag1', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag2', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag3', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag4', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag5', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag6', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag7', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag8', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag9', old_value => 'a', new_value => 'b' },
        { changed_field => 'mag10', old_value => 'a', new_value => 'b' },
#+END_SRC

* Fun With The Diagonal

change the lowercase characters on the main diagonal to uppercase

** Start file

#+BEGIN_SRC 
a a a a a
b b b b b
c c c c c
d d d d d
e e e e e
#+END_SRC

** End file

#+BEGIN_SRC 
A a a a a
b B b b b
c c C c c
d d d D d
e e e e E
#+END_SRC

* NBCU Weekly Challenge - #0

One of our favorites lines here at NBCU! p.s. The first version of #0 was deleted due to me copy/pasting a HTML entity. Congrats to the one who figured that out, you are a true ninja warrior!

** Start file

#+BEGIN_SRC 
Mosst importantly, where making the world an better place through constructing elegant heirarchies for mimimun code reuse and extensibility?
#+END_SRC

** End file

#+BEGIN_SRC 
Most importantly, we're making the world a better place through constructing elegant hierarchies for maximum code reuse and extensibility.
#+END_SRC

* Refactor arguments into object argument

A relatively common Javascript refactoring.
** Start file

#+BEGIN_SRC 
function foo(hello, world,
             how, are,
             you) {
}
#+END_SRC

** End file

#+BEGIN_SRC 
function foo(parameters) {
    var hello = parameters.hello;
    var world = parameters.world;
    var how = parameters.how;
    var are = parameters.are;
    var you = parameters.you;
}
#+END_SRC

* Shuffle and Sort

The values where sorted incorrectly. Get them back to how they are supposed to be

** Start file

#+BEGIN_SRC 
a,b,c,d,e
a,b,c,d,e
a,b,c,d,e
a,b,c,d,e
a,b,c,d,e
#+END_SRC

** End file

#+BEGIN_SRC 
d,e,a,b,c
e,a,b,c,d
a,b,c,d,e
b,c,d,e,a
c,d,e,a,b
#+END_SRC

* Assign list

Assign list elements to matrix
** Start file

#+BEGIN_SRC 
A challenge can hide secrets

  M00 =
  M01 =
  M10 =
  M11 =
  M20 =
  M21 = 0
#+END_SRC

** End file

#+BEGIN_SRC 
  M[0][0] = 'A'
  M[0][1] = 'challenge'
  M[1][0] = 'can'
  M[1][1] = 'hide'
  M[2][0] = 'secrets'
  M[2][1] = 0
#+END_SRC

* Winning streak

Make the number on each line equal the consecutive L's or W's.

** Start file

#+BEGIN_SRC 
W 1
W 1
W 1
L 1
L 1
W 1
L 1
L 1
L 1
W 1
W 1
W 1
L 1
W 1
W 1
W 1
W 1
L 1
L 1
L 1
#+END_SRC

** End file

#+BEGIN_SRC 
W 1
W 2
W 3
L 1
L 2
W 1
L 1
L 2
L 3
W 1
W 2
W 3
L 1
W 1
W 2
W 3
W 4
L 1
L 2
L 3
#+END_SRC

* Block Fun 1

Manipulate the columns to produce desired result.

** Start file

#+BEGIN_SRC 
01234567890123456789012345678901234567890123456789012345678901234567890123456789
1                                                                              0
2                                                                              1
3                                                                              2
4                                                                              3
5                                                                              4
6                                                                              5
7                                                                              6
8                                                                              7
9                                                                              8
01234567890123456789012345678901234567890123456789012345678901234567890123456789
#+END_SRC

** End file

#+BEGIN_SRC 
01234567890123456789012345678901234567890123456789012345678901234567890123456789
1        0         0         0         0         0         0         0         0
2        1         1         1         1         1         1         1         1
3        2         2         2         2         2         2         2         2
4        3         3         3         3         3         3         3         3
5        4         4         4         4         4         4         4         4
6        5         5         5         5         5         5         5         5
7        6         6         6         6         6         6         6         6
8        7         7         7         7         7         7         7         7
9        8         8         8         8         8         8         8         8
01234567890123456789012345678901234567890123456789012345678901234567890123456789
#+END_SRC

* Cartesian product

{1,2,3,4,5} X {1,2,3,4,5}
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
1 1
1 2
1 3
1 4
1 5
2 1
2 2
2 3
2 4
2 5
3 1
3 2
3 3
3 4
3 5
4 1
4 2
4 3
4 4
4 5
5 1
5 2
5 3
5 4
5 5
#+END_SRC

* Hidden Message

Find the hidden message and replace all other characters with spaces.
** Start file

#+BEGIN_SRC 
ubkptcgbjc
vhellosqgf
abpnvazvgc
eycbkcnicm
qyinexvmxf
rlgmffufur
ybdokpsfxm
znfrlyaazb
zeunlfkmfe
emlzsfgnlj
#+END_SRC
** End file

#+BEGIN_SRC 
          
 hello    
       v  
       i  
       m  
  g       
   o      
    l     
     f    
          
#+END_SRC

* Generate Fibonacci Numbers

Use your super vim powers to generate Fibonacci Numbers.
** Start file

#+BEGIN_SRC 
0
#+END_SRC
** End file

#+BEGIN_SRC 
0
1
1
2
3
5
8
13
21
34
55
89
144
233
377
610
987
1597
2584
4181
6765
10946
17711
28657
46368
75025
121393
196418
317811
514229
832040
1346269
2178309
3524578
5702887
9227465
14930352
24157817
39088169
#+END_SRC

* Another Mixed-Up Haiku

VimGolf ... a perfect evening?
** Start file
#+BEGIN_SRC 
Eemplt Sellb Eid Tuo.
Eht Tragranf Slossomb Nemair.
A Terfecp Gvenine!
#+END_SRC

** End file

#+BEGIN_SRC 
Temple bells die out.
The fragrant blossoms remain.
A perfect evening!
#+END_SRC

* It'ss tooo coold too typpe todaay

My hands are numb with cold. It's hard to type correctly.
** Start file

#+BEGIN_SRC 
VIM IS... MULTI PLATFORM                                *design-multi-platform*

Vim tries to heelp as manny ussers onn as mmany platfoorms as posssible.
- Support many kinds of terminals.  The minimal demands are cursor positioning
  and clear-screen.  Commands should only use key strokes that most keyboards
  have.  Suppport alll teh keyys on hte keybooard forr mappping.
- Support many platforms.  A condition is that there is someone willing to do
  Vim development on that platform, and it doesn't mean messing up the code.
- Support many compilers and libraries.  Not everybody is able or allowed to
  installl anotherr compiller or GUI libraryy.
- Peeople switch from one plattform to another, andd from GUI to terminal
  version.  Features should be present in all versions, or at least in as many
  as posssible with a reasonable effort.  Try to avoid that users must switch
  betweeen platforms to acccomplish theirr workk effficiently.
- That a feature is not posssible on some platforms, or only posssible on one
  platform, does not mean it cannnot be implemented.  [This intentionallly
  contradicts teh previous item, these two must be balanced.]
#+END_SRC

** End file

#+BEGIN_SRC 
VIM IS... MULTI PLATFORM                                *design-multi-platform*

Vim tries to help as many users on as many platforms as possible.
- Support many kinds of terminals.  The minimal demands are cursor positioning
  and clear-screen.  Commands should only use key strokes that most keyboards
  have.  Support all the keys on the keyboard for mapping.
- Support many platforms.  A condition is that there is someone willing to do
  Vim development on that platform, and it doesn't mean messing up the code.
- Support many compilers and libraries.  Not everybody is able or allowed to
  install another compiler or GUI library.
- People switch from one platform to another, and from GUI to terminal
  version.  Features should be present in all versions, or at least in as many
  as possible with a reasonable effort.  Try to avoid that users must switch
  between platforms to accomplish their work efficiently.
- That a feature is not possible on some platforms, or only possible on one
  platform, does not mean it cannot be implemented.  [This intentionally
  contradicts the previous item, these two must be balanced.]
#+END_SRC

* Dehamlizing

Change this piece of HAML code back into erb
** Start file
#+BEGIN_SRC 
%tr
  %td= raw("<%= line1_hello %>")
  %td= raw("<%= line2(world) %>")
  %td= raw("<%= line3_hello %>")
  %td= raw("<%= line4 %>")
  %td= raw("<%= line5_(world) %>")
#+END_SRC
** End file

#+BEGIN_SRC 
<tr>
  <td><%= line1_hello %></td>
  <td><%= line2(world) %></td>
  <td><%= line3_hello %></td>
  <td><%= line4 %></td>
  <td><%= line5_(world) %></td>
</tr>
#+END_SRC

* PHP <--> Java class conversion Part 1

Convert this tiny php class to adequate java one.
** Start file

#+BEGIN_SRC 
<?php
class Foo
{
        private $var1;
        private $var2;

        public function Foo($val)
        {
                $this->init($val);
                $this->doSomething();
        }

        private function init($val)
        {
                $this->var1 = $val;
        }
        
        private function doSomething()
        {
                $this->var2 = sqrt($this->var1);
        }

        public function getResult()
        {
                return $this->var2;
        }
}
?>
#+END_SRC
** End file

#+BEGIN_SRC 
public class Foo
{
        private double var1;
        private double var2;

        public Foo(double val)
        {
                init(val);
                doSomething();
        }

        private void init(double val)
        {
                var1 = val;
        }
        
        private void doSomething()
        {
                var2 = Math.sqrt(var1);
        }

        public double getResult()
        {
                return var2;
        }
}
#+END_SRC

* Separating firstname & lastname

Seperate named with equal tabs.
** Start file
#+BEGIN_SRC 
Johm Smith
Mary Gold
Alfred Quinn
Michal Jackson
Zeeshan Jan
#+END_SRC
** End file

#+BEGIN_SRC 
John          Smith
Mary          Gold
Alfred        Quinn
Michal        Jackson
Zeeshan       Jan
#+END_SRC

* Assign numbers to fields

You are given a list of space-separated strings. Add an increasing numeric prefix to each one.

** Start file
#+BEGIN_SRC 
CHROM POS ID REF ALT QUAL FILTER INFO FORMAT
#+END_SRC

** End file

#+BEGIN_SRC 
0:CHROM 1:POS 2:ID 3:REF 4:ALT 5:QUAL 6:FILTER 7:INFO 8:FORMAT
#+END_SRC

* Piphilology

Piphilology comprises the creation and use of mnemonic techniques to remember a span of digits of the mathematical constant π. http://en.wikipedia.org/wiki/Piphilology

** Start file

Sir, I bear a rhyme excelling
In mystic force and magic spelling
Celestial sprites elucidate
All my own striving cant relate
Or locate they who can cogitate
And so finally terminate. Finis.
#+END_SRC
** End file

#+BEGIN_SRC 
3.1415926535897932384626433832795
#+END_SRC
 
* swap or reverse

Try to swap or reverse the line as needed.
** Start file
#+BEGIN_SRC 
abcdefghijklmn
#+END_SRC
** End file

#+BEGIN_SRC 
abcdefghijklmn
bcdefghijklmna
cdefghijklmnba
defghijklmncba
efghijklmndcba
fghijklmnedcba
ghijklmnfedcba
hijklmngfedcba
ijklmnhgfedcba
jklmnihgfedcba
klmnjihgfedcba
lmnkjihgfedcba
mnlkjihgfedcba
nmlkjihgfedcba
#+END_SRC

* constructor

coding a constructor for a simple class
** Start file
#+BEGIN_SRC 
class SongEntry
{
public:
    SongEntry
        (
        QString mSinger = QString(),
        QString mSongName = QString(),
        QString mGender = QString(),
        QString mSongLang = QString(),
        int mSongLength = 0,
        QString mSongPath = QString(),
        QString mNotes = QString()
        );

private:
    int mId;
    QString mSinger;
    QString mSongName;
    QString mGender;
    QString mSongLang;
    int mSongLength; // in seconds
    QString mSongPath;
    QString mNotes;
};

===========================================================
#+END_SRC

** End file

#+BEGIN_SRC 
class SongEntry
{
public:
    SongEntry
        (
        QString mSinger = QString(),
        QString mSongName = QString(),
        QString mGender = QString(),
        QString mSongLang = QString(),
        int mSongLength = 0,
        QString mSongPath = QString(),
        QString mNotes = QString()
        );

private:
    int mId;
    QString mSinger;
    QString mSongName;
    QString mGender;
    QString mSongLang;
    int mSongLength; // in seconds
    QString mSongPath;
    QString mNotes;
};

===========================================================

SongEntry::SongEntry
    (
    QString aSinger,
    QString aSongName,
    QString aGender,
    QString aSongLang,
    int aSongLength,
    QString aSongPath,
    QString aNotes
    )
    : mSinger( aSinger )
    , mSongName( aSongName )
    , mGender( aGender )
    , mSongLang( aSongLang )
    , mSongLength( aSongLength )
    , mSongPath( aSongPath )
    , mNotes( aNotes )
{
}
#+END_SRC

* Aligning function arguments to match a specific coding style

Most projects have specific coding style guidelines. In this case, the argument list must be broken into a new line for each argument, with the argument names right aligned, taking into account pointers.
** Start file
#+BEGIN_SRC 
void
clutter_layout_manager_get_preferred_width (ClutterActor *actor,
                                            ClutterContainer *container,
                                            gfloat for_width,
                                            gfloat *min_width_p,
                                            gfloat *natural_width_p)
{
}
#+END_SRC
** End file

#+BEGIN_SRC 
void
clutter_layout_manager_get_preferred_width (ClutterActor     *actor,
                                            ClutterContainer *container,
                                            gfloat            for_width,
                                            gfloat           *min_width_p,
                                            gfloat           *natural_width_p)
{
}
#+END_SRC
* formatted text to markdown

You're converting some posts from an old blog to markdown. The formatted text is far closer to the finished product than the html markup, so it seems like a good place to start. Word wrapping seems to be the main area for optimization.
** Start file
#+BEGIN_SRC 
But I think that there will still be many uses for publications. To have many articles bound together into a group. A magazine. A book. An album. And I haven't seen this done very well, up to this point. (Several e-zines I've seen just release a PDF, which I resent.) Though perhaps I have not seen it done well because I haven't looked much—I have seen an online-novel-in-process, which gives some vague notion of length via the prominent Table of Contents, but nothing as tangible even as a scrollbar or page numbers all lined up. And certainly not as tangible as a physical depth in my hands.
#+END_SRC
** End file

#+BEGIN_SRC 
But I think that there will still be many uses for publications. To
have many articles bound together into a group. A magazine. A book.
An album. And I haven't seen this done very well, up to this point.
(Several e-zines I've seen just release a PDF, which I resent.)
Though perhaps I have not seen it done well because I haven't looked
much&mdash;I have seen an [online-novel-in-process][1], which gives some vague
notion of length via the prominent Table of Contents, but nothing as
tangible even as a scrollbar or page numbers all lined up. And
certainly not as tangible as a physical depth in my hands.

  [1]: http://www.greengreenmud.com/
#+END_SRC

* ASCII Art

how good are you with simple regex?
** Start file
#+BEGIN_SRC 
 #_                                                                       d
 ##_                                                                     d#
 NN#p                                                                  j0NN
 40NNh_                                                              _gN#B0
 4JF@NNp_                                                          _g0WNNL@
 JLE5@WRNp_                                                      _g@NNNF3_L
 _F`@q4WBN@Np_                                                _gNN@ZL#p"Fj_
 "0^#-LJ_9"NNNMp__                                         _gN#@#"R_#g@q^9"
 a0,3_j_j_9FN@N@0NMp__                                __ggNZNrNM"P_f_f_E,0a
  j  L 6 9""Q"#^q@NDNNNMpg____                ____gggNNW#W4p^p@jF"P"]"j  F
 rNrr4r*pr4r@grNr@q@Ng@q@N0@N#@NNMpmggggmqgNN@NN@#@4p*@M@p4qp@w@m@Mq@r#rq@r
   F Jp 9__b__M,Juw*w*^#^9#""EED*dP_@EZ@^E@*#EjP"5M"gM@p*Ww&,jL_J__f  F j
 -r#^^0""E" 6  q  q__hg-@4""*,_Z*q_"^pwr""p*C__@""0N-qdL_p" p  J" 3""5^^0r-
   t  J  __,Jb--N""",  *_s0M`""q_a@NW__JP^u_p"""p4a,p" _F""V--wL,_F_ F  #
 _,Jp*^#""9   L  5_a*N"""q__INr" "q_e^"*,p^""qME_ y"""p6u,f  j'  f "N^--LL_
    L  ]   k,w@#"""_  "_a*^E   ba-" ^qj-""^pe"  J^-u_f  _f "q@w,j   f  jL
    #_,J@^""p  `_ _jp-""q  _Dw^" ^cj*""*,j^  "p#_  y""^wE_ _F   F"^qN,_j
 w*^0   4   9__sAF" `L  _Dr"  m__m""q__a^"m__*  "qA_  j" ""Au__f   J   0^--
    ]   J_,x-E   3_  jN^" `u _w^*_  _RR_  _J^w_ j"  "pL_  f   7^-L_F   #
    jLs*^6   `_  _&*"  q  _,NF   "wp"  "*g"   _NL_  p  "-d_   F   ]"*u_F
 ,x-"F   ]    Ax^" q    hp"  `u jM""u  a^ ^, j"  "*g_   p  ^mg_   D.H. 1992
#+END_SRC
** End file

#+BEGIN_SRC 
 ,x-"F   ]    Ax^" q    hp"  `u jM""u  a^ ^, j"  "*g_   p  ^mg_   D.H. 1992
    jLs*^6   `_  _&*"  q  _,NF   "wp"  "*g"   _NL_  p  "-d_   F   ]"*u_F
    ]   J_,x-E   3_  jN^" `u _w^*_  _RR_  _J^w_ j"  "pL_  f   7^-L_F   #
 w*^0   4   9__sAF" `L  _Dr"  m__m""q__a^"m__*  "qA_  j" ""Au__f   J   0^--
    #_,J@^""p  `_ _jp-""q  _Dw^" ^cj*""*,j^  "p#_  y""^wE_ _F   F"^qN,_j
    L  ]   k,w@#"""_  "_a*^E   ba-" ^qj-""^pe"  J^-u_f  _f "q@w,j   f  jL
 _,Jp*^#""9   L  5_a*N"""q__INr" "q_e^"*,p^""qME_ y"""p6u,f  j'  f "N^--LL_
   t  J  __,Jb--N""",  *_s0M`""q_a@NW__JP^u_p"""p4a,p" _F""V--wL,_F_ F  #
 -r#^^0""E" 6  q  q__hg-@4""*,_Z*q_"^pwr""p*C__@""0N-qdL_p" p  J" 3""5^^0r-
   F Jp 9__b__M,Juw*w*^#^9#""EED*dP_@EZ@^E@*#EjP"5M"gM@p*Ww&,jL_J__f  F j
 rNrr4r*pr4r@grNr@q@Ng@q@N0@N#@NNMpmggggmqgNN@NN@#@4p*@M@p4qp@w@m@Mq@r#rq@r
  j  L 6 9""Q"#^q@NDNNNMpg____                ____gggNNW#W4p^p@jF"P"]"j  F
 a0,3_j_j_9FN@N@0NMp__                                __ggNZNrNM"P_f_f_E,0a
 "0^#-LJ_9"NNNMp__                                         _gN#@#"R_#g@q^9"
 _F`@q4WBN@Np_                                                _gNN@ZL#p"Fj_
 JLE5@WRNp_                                                      _g@NNNF3_L
 4JF@NNp_                                                          _g0WNNL@
 40NNh_                                                              _gN#B0
 NN#p                                                                  j0NN
 ##_                                                                     d#
 #_                                                                       d
 #_                                                                       d
 ##_                                                                     d#
 NN#p                                                                  j0NN
 40NNh_                                                              _gN#B0
 4JF@NNp_                                                          _g0WNNL@
 JLE5@WRNp_                                                      _g@NNNF3_L
 _F`@q4WBN@Np_                                                _gNN@ZL#p"Fj_
 "0^#-LJ_9"NNNMp__                                         _gN#@#"R_#g@q^9"
 a0,3_j_j_9FN@N@0NMp__                                __ggNZNrNM"P_f_f_E,0a
  j  L 6 9""Q"#^q@NDNNNMpg____                ____gggNNW#W4p^p@jF"P"]"j  F
 rNrr4r*pr4r@grNr@q@Ng@q@N0@N#@NNMpmggggmqgNN@NN@#@4p*@M@p4qp@w@m@Mq@r#rq@r
   F Jp 9__b__M,Juw*w*^#^9#""EED*dP_@EZ@^E@*#EjP"5M"gM@p*Ww&,jL_J__f  F j
 -r#^^0""E" 6  q  q__hg-@4""*,_Z*q_"^pwr""p*C__@""0N-qdL_p" p  J" 3""5^^0r-
   t  J  __,Jb--N""",  *_s0M`""q_a@NW__JP^u_p"""p4a,p" _F""V--wL,_F_ F  #
 _,Jp*^#""9   L  5_a*N"""q__INr" "q_e^"*,p^""qME_ y"""p6u,f  j'  f "N^--LL_
    L  ]   k,w@#"""_  "_a*^E   ba-" ^qj-""^pe"  J^-u_f  _f "q@w,j   f  jL
    #_,J@^""p  `_ _jp-""q  _Dw^" ^cj*""*,j^  "p#_  y""^wE_ _F   F"^qN,_j
 w*^0   4   9__sAF" `L  _Dr"  m__m""q__a^"m__*  "qA_  j" ""Au__f   J   0^--
    ]   J_,x-E   3_  jN^" `u _w^*_  _RR_  _J^w_ j"  "pL_  f   7^-L_F   #
    jLs*^6   `_  _&*"  q  _,NF   "wp"  "*g"   _NL_  p  "-d_   F   ]"*u_F
 ,x-"F   ]    Ax^" q    hp"  `u jM""u  a^ ^, j"  "*g_   p  ^mg_   D.H. 1992
#+END_SRC

* Turn this csv list into queries

Transform each line of this csv file into a MySQL-ready INSERT query.
** Start file
#+BEGIN_SRC 
id 1,Item 1,cost 1,location 1
id 2,Item 2,cost 2,location 2
id 3,Item 3,cost 3,location 3
id 4,Item 4,cost 4,location 4
id 5,Item 5,cost 5,location 5
id 6,Item 6,cost 6,location 6
id 7,Item 7,cost 7,location 7
id 8,Item 8,cost 8,location 8
id 9,Item 9,cost 9,location 9
id 10,Item 10,cost 10,location 10
id 11,Item 11,cost 11,location 11
id 12,Item 12,cost 12,location 12
id 13,Item 13,cost 13,location 13
id 14,Item 14,cost 14,location 14
id 15,Item 15,cost 15,location 15
id 16,Item 16,cost 16,location 16
id 17,Item 17,cost 17,location 17
id 18,Item 18,cost 18,location 18
id 19,Item 19,cost 19,location 19
id 20,Item 20,cost 20,location 20
id 21,Item 21,cost 21,location 21
id 22,Item 22,cost 22,location 22
id 23,Item 23,cost 23,location 23
id 24,Item 24,cost 24,location 24
id 25,Item 25,cost 25,location 25
id 26,Item 26,cost 26,location 26
id 27,Item 27,cost 27,location 27
id 28,Item 28,cost 28,location 28
id 29,Item 29,cost 29,location 29
id 30,Item 30,cost 30,location 30
id 31,Item 31,cost 31,location 31
id 32,Item 32,cost 32,location 32
id 33,Item 33,cost 33,location 33
id 34,Item 34,cost 34,location 34
id 35,Item 35,cost 35,location 35
id 36,Item 36,cost 36,location 36
id 37,Item 37,cost 37,location 37
id 38,Item 38,cost 38,location 38
id 39,Item 39,cost 39,location 39
id 40,Item 40,cost 40,location 40
id 41,Item 41,cost 41,location 41
id 42,Item 42,cost 42,location 42
id 43,Item 43,cost 43,location 43
id 44,Item 44,cost 44,location 44
id 45,Item 45,cost 45,location 45
id 46,Item 46,cost 46,location 46
id 47,Item 47,cost 47,location 47
id 48,Item 48,cost 48,location 48
id 49,Item 49,cost 49,location 49
id 50,Item 50,cost 50,location 50
#+END_SRC
** End file

#+BEGIN_SRC 
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 1','Item 1','Cost 1','Location 1'); 
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 2','Item 2','Cost 2','Location 2');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 3','Item 3','Cost 3','Location 3');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 4','Item 4','Cost 4','Location 4');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 5','Item 5','Cost 5','Location 5');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 6','Item 6','Cost 6','Location 6');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 7','Item 7','Cost 7','Location 7');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 8','Item 8','Cost 8','Location 8');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 9','Item 9','Cost 9','Location 9');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 10','Item 10','Cost 10','Location 10');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 11','Item 11','Cost 11','Location 11');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 12','Item 12','Cost 12','Location 12');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 13','Item 13','Cost 13','Location 13');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 14','Item 14','Cost 14','Location 14');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 15','Item 15','Cost 15','Location 15');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 16','Item 16','Cost 16','Location 16');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 17','Item 17','Cost 17','Location 17');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 18','Item 18','Cost 18','Location 18');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 19','Item 19','Cost 19','Location 19');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 20','Item 20','Cost 20','Location 20');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 21','Item 21','Cost 21','Location 21');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 22','Item 22','Cost 22','Location 22');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 23','Item 23','Cost 23','Location 23');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 24','Item 24','Cost 24','Location 24');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 25','Item 25','Cost 25','Location 25');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 26','Item 26','Cost 26','Location 26');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 27','Item 27','Cost 27','Location 27');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 28','Item 28','Cost 28','Location 28');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 29','Item 29','Cost 29','Location 29');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 30','Item 30','Cost 30','Location 30');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 31','Item 31','Cost 31','Location 31');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 32','Item 32','Cost 32','Location 32');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 33','Item 33','Cost 33','Location 33');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 34','Item 34','Cost 34','Location 34');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 35','Item 35','Cost 35','Location 35');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 36','Item 36','Cost 36','Location 36');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 37','Item 37','Cost 37','Location 37');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 38','Item 38','Cost 38','Location 38');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 39','Item 39','Cost 39','Location 39');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 40','Item 40','Cost 40','Location 40');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 41','Item 41','Cost 41','Location 41');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 42','Item 42','Cost 42','Location 42');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 43','Item 43','Cost 43','Location 43');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 44','Item 44','Cost 44','Location 44');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 45','Item 45','Cost 45','Location 45');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 46','Item 46','Cost 46','Location 46');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 47','Item 47','Cost 47','Location 47');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 48','Item 48','Cost 48','Location 48');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 49','Item 49','Cost 49','Location 49');
INSERT INTO `database`.`table` (`id` ,`item` ,`cost` ,`location`) VALUES ('id 50','Item 50','Cost 50','Location 50');
#+END_SRC

* Complete the hex array data

Do not use external tools(e.g. tac, seq) [My interpretation of Rule #7]
** Start file

#+BEGIN_SRC 
unsigned int hex[] = {
        0x00, 0x01, 0x02, 0x03, 0x04, 0x05, 0x06, 0x07,
        0x08, 0x09, 0x0a, 0x0b, 0x0c, 0x0d, 0x0e, 0x0f, 
};
#+END_SRC
** End file

#+BEGIN_SRC 
unsigned int hex[] = {
        0x00, 0x01, 0x02, 0x03, 0x04, 0x05, 0x06, 0x07,
        0x08, 0x09, 0x0a, 0x0b, 0x0c, 0x0d, 0x0e, 0x0f, 
        0x10, 0x11, 0x12, 0x13, 0x14, 0x15, 0x16, 0x17,
        0x18, 0x19, 0x1a, 0x1b, 0x1c, 0x1d, 0x1e, 0x1f, 
        0x20, 0x21, 0x22, 0x23, 0x24, 0x25, 0x26, 0x27,
        0x28, 0x29, 0x2a, 0x2b, 0x2c, 0x2d, 0x2e, 0x2f, 
        0x30, 0x31, 0x32, 0x33, 0x34, 0x35, 0x36, 0x37,
        0x38, 0x39, 0x3a, 0x3b, 0x3c, 0x3d, 0x3e, 0x3f, 
        0x40, 0x41, 0x42, 0x43, 0x44, 0x45, 0x46, 0x47,
        0x48, 0x49, 0x4a, 0x4b, 0x4c, 0x4d, 0x4e, 0x4f, 
        0x50, 0x51, 0x52, 0x53, 0x54, 0x55, 0x56, 0x57,
        0x58, 0x59, 0x5a, 0x5b, 0x5c, 0x5d, 0x5e, 0x5f, 
        0x60, 0x61, 0x62, 0x63, 0x64, 0x65, 0x66, 0x67,
        0x68, 0x69, 0x6a, 0x6b, 0x6c, 0x6d, 0x6e, 0x6f, 
        0x70, 0x71, 0x72, 0x73, 0x74, 0x75, 0x76, 0x77,
        0x78, 0x79, 0x7a, 0x7b, 0x7c, 0x7d, 0x7e, 0x7f, 
        0x80, 0x81, 0x82, 0x83, 0x84, 0x85, 0x86, 0x87,
        0x88, 0x89, 0x8a, 0x8b, 0x8c, 0x8d, 0x8e, 0x8f, 
        0x90, 0x91, 0x92, 0x93, 0x94, 0x95, 0x96, 0x97,
        0x98, 0x99, 0x9a, 0x9b, 0x9c, 0x9d, 0x9e, 0x9f, 
        0xa0, 0xa1, 0xa2, 0xa3, 0xa4, 0xa5, 0xa6, 0xa7,
        0xa8, 0xa9, 0xaa, 0xab, 0xac, 0xad, 0xae, 0xaf, 
        0xb0, 0xb1, 0xb2, 0xb3, 0xb4, 0xb5, 0xb6, 0xb7,
        0xb8, 0xb9, 0xba, 0xbb, 0xbc, 0xbd, 0xbe, 0xbf, 
        0xc0, 0xc1, 0xc2, 0xc3, 0xc4, 0xc5, 0xc6, 0xc7,
        0xc8, 0xc9, 0xca, 0xcb, 0xcc, 0xcd, 0xce, 0xcf, 
        0xd0, 0xd1, 0xd2, 0xd3, 0xd4, 0xd5, 0xd6, 0xd7,
        0xd8, 0xd9, 0xda, 0xdb, 0xdc, 0xdd, 0xde, 0xdf, 
        0xe0, 0xe1, 0xe2, 0xe3, 0xe4, 0xe5, 0xe6, 0xe7,
        0xe8, 0xe9, 0xea, 0xeb, 0xec, 0xed, 0xee, 0xef, 
        0xf0, 0xf1, 0xf2, 0xf3, 0xf4, 0xf5, 0xf6, 0xf7,
        0xf8, 0xf9, 0xfa, 0xfb, 0xfc, 0xfd, 0xfe, 0xff, 
};
#+END_SRC

* Multiplication table.

Create a multiplication table.
** Start file

1
#+END_SRC
** End file

#+BEGIN_SRC 
1   2   3   4   5   6   7   8   9   10
2   4   6   8   10  12  14  16  18  20
3   6   9   12  15  18  21  24  27  30
4   8   12  16  20  24  28  32  36  40
5   10  15  20  25  30  35  40  45  50
6   12  18  24  30  36  42  48  54  60  
7   14  21  28  35  42  49  56  63  70
8   16  24  32  40  48  56  64  72  80
9   18  27  36  45  54  63  72  81  90
10  20  30  40  50  60  70  80  90  100
#+END_SRC

* SFD-ROC: The Quick Brown Fox

Someone has vandalized our text (again). Please fix to read: The Quick Brown Fox Jumps Over The Lazy Dog.
** Start file
#+BEGIN_SRC 
ThX QuicX BrowX FoX JumpX OveX ThX LazX DoX.

#+END_SRC
** End file

#+BEGIN_SRC 
The Quick Brown Fox Jumps Over The Lazy Dog.
#+END_SRC

* Groups magic

Regexp or macros for string converting: (a) -> ___ (abc) -> ____ (abcd) -> ______ All in the '(' replace to _ multiply by char count + ()
** Start file

#+BEGIN_SRC 
(a) (abc) (abcd) (123456)
#+END_SRC

** End file
#+BEGIN_SRC 
___ _____ ______ ________
#+END_SRC

* Unwrap the text of an email message

Reverse of "Wrap the text of an email message to 79 characters". gq and gw are great for wrapping paragraphs. But sometimes other programs choke on your wrapped lines. What's the best way to un-gq?
** Start file
#+BEGIN_SRC 
> "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
> doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
> veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim
> ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

> Sed quia consequuntur magni dolores eos qui ratione voluptatem sequi
> nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet,
> consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt
> ut labore et dolore magnam aliquam quaerat voluptatem.

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit
laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure
reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur,
vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
#+END_SRC

** End file
#+BEGIN_SRC 
> "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

> Sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.

Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
#+END_SRC

* REDRUM

If you remember "The Shinning", the first time you saw the bloody word REDRUM you probably thinked "What the Hell is that?" Well, then you know that you need a little help from a looking-glass to make sense of it. Now it's time to use vim like a mirror to reveal the message.
** Start file
#+BEGIN_SRC 
nac uoy ro ,rorrim a ni siht daer ot evah uoy ,redrum eht hctac ot tnaw uoy fI
); miV esu

.omodrojam eht ...si redrum ehT
#+END_SRC

** End file
#+BEGIN_SRC 
If you want to catch the murder, you have to read this in a mirror, or you can
use Vim ;)

The murder is... the majordomo.
#+END_SRC

* Long prime list - filter version

I've used the maximum input/diff/output size allowed by vimgolf to get a list of integers up to 1460 separated by newlines, and your goal is to only keep the lines containing primes. There are 232 of them I hope some of you will golf vimscript itself to create some function to run as a primality check for each line, which is a good exercise if you haven't done much vimscript yet! You're invited to also try copy-pasting and doing other non-smart text manipulation. Even more interesting would be to see a solution that uses text manipulation to do the filtering! Whether you use vimscript, normal-mode primality checks, or text manipulation, as long as the end result is valid, your answer will be valid! Let's see which method does better here. Best of luck!
** Start file
#+BEGIN_SRC 
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
121
122
123
124
125
126
127
128
129
130
131
132
133
134
135
136
137
138
139
140
141
142
143
144
145
146
147
148
149
150
151
152
153
154
155
156
157
158
159
160
161
162
163
164
165
166
167
168
169
170
171
172
173
174
175
176
177
178
179
180
181
182
183
184
185
186
187
188
189
190
191
192
193
194
195
196
197
198
199
200
201
202
203
204
205
206
207
208
209
210
211
212
213
214
215
216
217
218
219
220
221
222
223
224
225
226
227
228
229
230
231
232
233
234
235
236
237
238
239
240
241
242
243
244
245
246
247
248
249
250
251
252
253
254
255
256
257
258
259
260
261
262
263
264
265
266
267
268
269
270
271
272
273
274
275
276
277
278
279
280
281
282
283
284
285
286
287
288
289
290
291
292
293
294
295
296
297
298
299
300
301
302
303
304
305
306
307
308
309
310
311
312
313
314
315
316
317
318
319
320
321
322
323
324
325
326
327
328
329
330
331
332
333
334
335
336
337
338
339
340
341
342
343
344
345
346
347
348
349
350
351
352
353
354
355
356
357
358
359
360
361
362
363
364
365
366
367
368
369
370
371
372
373
374
375
376
377
378
379
380
381
382
383
384
385
386
387
388
389
390
391
392
393
394
395
396
397
398
399
400
401
402
403
404
405
406
407
408
409
410
411
412
413
414
415
416
417
418
419
420
421
422
423
424
425
426
427
428
429
430
431
432
433
434
435
436
437
438
439
440
441
442
443
444
445
446
447
448
449
450
451
452
453
454
455
456
457
458
459
460
461
462
463
464
465
466
467
468
469
470
471
472
473
474
475
476
477
478
479
480
481
482
483
484
485
486
487
488
489
490
491
492
493
494
495
496
497
498
499
500
501
502
503
504
505
506
507
508
509
510
511
512
513
514
515
516
517
518
519
520
521
522
523
524
525
526
527
528
529
530
531
532
533
534
535
536
537
538
539
540
541
542
543
544
545
546
547
548
549
550
551
552
553
554
555
556
557
558
559
560
561
562
563
564
565
566
567
568
569
570
571
572
573
574
575
576
577
578
579
580
581
582
583
584
585
586
587
588
589
590
591
592
593
594
595
596
597
598
599
600
601
602
603
604
605
606
607
608
609
610
611
612
613
614
615
616
617
618
619
620
621
622
623
624
625
626
627
628
629
630
631
632
633
634
635
636
637
638
639
640
641
642
643
644
645
646
647
648
649
650
651
652
653
654
655
656
657
658
659
660
661
662
663
664
665
666
667
668
669
670
671
672
673
674
675
676
677
678
679
680
681
682
683
684
685
686
687
688
689
690
691
692
693
694
695
696
697
698
699
700
701
702
703
704
705
706
707
708
709
710
711
712
713
714
715
716
717
718
719
720
721
722
723
724
725
726
727
728
729
730
731
732
733
734
735
736
737
738
739
740
741
742
743
744
745
746
747
748
749
750
751
752
753
754
755
756
757
758
759
760
761
762
763
764
765
766
767
768
769
770
771
772
773
774
775
776
777
778
779
780
781
782
783
784
785
786
787
788
789
790
791
792
793
794
795
796
797
798
799
800
801
802
803
804
805
806
807
808
809
810
811
812
813
814
815
816
817
818
819
820
821
822
823
824
825
826
827
828
829
830
831
832
833
834
835
836
837
838
839
840
841
842
843
844
845
846
847
848
849
850
851
852
853
854
855
856
857
858
859
860
861
862
863
864
865
866
867
868
869
870
871
872
873
874
875
876
877
878
879
880
881
882
883
884
885
886
887
888
889
890
891
892
893
894
895
896
897
898
899
900
901
902
903
904
905
906
907
908
909
910
911
912
913
914
915
916
917
918
919
920
921
922
923
924
925
926
927
928
929
930
931
932
933
934
935
936
937
938
939
940
941
942
943
944
945
946
947
948
949
950
951
952
953
954
955
956
957
958
959
960
961
962
963
964
965
966
967
968
969
970
971
972
973
974
975
976
977
978
979
980
981
982
983
984
985
986
987
988
989
990
991
992
993
994
995
996
997
998
999
1000
1001
1002
1003
1004
1005
1006
1007
1008
1009
1010
1011
1012
1013
1014
1015
1016
1017
1018
1019
1020
1021
1022
1023
1024
1025
1026
1027
1028
1029
1030
1031
1032
1033
1034
1035
1036
1037
1038
1039
1040
1041
1042
1043
1044
1045
1046
1047
1048
1049
1050
1051
1052
1053
1054
1055
1056
1057
1058
1059
1060
1061
1062
1063
1064
1065
1066
1067
1068
1069
1070
1071
1072
1073
1074
1075
1076
1077
1078
1079
1080
1081
1082
1083
1084
1085
1086
1087
1088
1089
1090
1091
1092
1093
1094
1095
1096
1097
1098
1099
1100
1101
1102
1103
1104
1105
1106
1107
1108
1109
1110
1111
1112
1113
1114
1115
1116
1117
1118
1119
1120
1121
1122
1123
1124
1125
1126
1127
1128
1129
1130
1131
1132
1133
1134
1135
1136
1137
1138
1139
1140
1141
1142
1143
1144
1145
1146
1147
1148
1149
1150
1151
1152
1153
1154
1155
1156
1157
1158
1159
1160
1161
1162
1163
1164
1165
1166
1167
1168
1169
1170
1171
1172
1173
1174
1175
1176
1177
1178
1179
1180
1181
1182
1183
1184
1185
1186
1187
1188
1189
1190
1191
1192
1193
1194
1195
1196
1197
1198
1199
1200
1201
1202
1203
1204
1205
1206
1207
1208
1209
1210
1211
1212
1213
1214
1215
1216
1217
1218
1219
1220
1221
1222
1223
1224
1225
1226
1227
1228
1229
1230
1231
1232
1233
1234
1235
1236
1237
1238
1239
1240
1241
1242
1243
1244
1245
1246
1247
1248
1249
1250
1251
1252
1253
1254
1255
1256
1257
1258
1259
1260
1261
1262
1263
1264
1265
1266
1267
1268
1269
1270
1271
1272
1273
1274
1275
1276
1277
1278
1279
1280
1281
1282
1283
1284
1285
1286
1287
1288
1289
1290
1291
1292
1293
1294
1295
1296
1297
1298
1299
1300
1301
1302
1303
1304
1305
1306
1307
1308
1309
1310
1311
1312
1313
1314
1315
1316
1317
1318
1319
1320
1321
1322
1323
1324
1325
1326
1327
1328
1329
1330
1331
1332
1333
1334
1335
1336
1337
1338
1339
1340
1341
1342
1343
1344
1345
1346
1347
1348
1349
1350
1351
1352
1353
1354
1355
1356
1357
1358
1359
1360
1361
1362
1363
1364
1365
1366
1367
1368
1369
1370
1371
1372
1373
1374
1375
1376
1377
1378
1379
1380
1381
1382
1383
1384
1385
1386
1387
1388
1389
1390
1391
1392
1393
1394
1395
1396
1397
1398
1399
1400
1401
1402
1403
1404
1405
1406
1407
1408
1409
1410
1411
1412
1413
1414
1415
1416
1417
1418
1419
1420
1421
1422
1423
1424
1425
1426
1427
1428
1429
1430
1431
1432
1433
1434
1435
1436
1437
1438
1439
1440
1441
1442
1443
1444
1445
1446
1447
1448
1449
1450
1451
1452
1453
1454
1455
1456
1457
1458
1459
1460
#+END_SRC

** End file
#+BEGIN_SRC 
2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89
97
101
103
107
109
113
127
131
137
139
149
151
157
163
167
173
179
181
191
193
197
199
211
223
227
229
233
239
241
251
257
263
269
271
277
281
283
293
307
311
313
317
331
337
347
349
353
359
367
373
379
383
389
397
401
409
419
421
431
433
439
443
449
457
461
463
467
479
487
491
499
503
509
521
523
541
547
557
563
569
571
577
587
593
599
601
607
613
617
619
631
641
643
647
653
659
661
673
677
683
691
701
709
719
727
733
739
743
751
757
761
769
773
787
797
809
811
821
823
827
829
839
853
857
859
863
877
881
883
887
907
911
919
929
937
941
947
953
967
971
977
983
991
997
1009
1013
1019
1021
1031
1033
1039
1049
1051
1061
1063
1069
1087
1091
1093
1097
1103
1109
1117
1123
1129
1151
1153
1163
1171
1181
1187
1193
1201
1213
1217
1223
1229
1231
1237
1249
1259
1277
1279
1283
1289
1291
1297
1301
1303
1307
1319
1321
1327
1361
1367
1373
1381
1399
1409
1423
1427
1429
1433
1439
1447
1451
1453
1459
#+END_SRC

* Inconsistent real estate paste

Format a hand-typed real estate listing that uses inconsistent punctuation into four sections
** Start file
#+BEGIN_SRC 
PROPERTY ADDRESS:  LOT 20, 10 FORTH LANE, WATERLOO, NC
ACREAGE - .842 ACRE
PRICE: - $140,500.00
CONTACT INFORMATION:   JOE & MARGE ALLAN
                                          81 RIDGE DRIVE
                                          PROVIDENCE, RI  02813
                                         1-555-231-2135
#+END_SRC

** End file
#+BEGIN_SRC 
PROPERTY ADDRESS

LOT 20, 10 FORTH LANE, WATERLOO, NC

ACREAGE

.842 ACRE

PRICE

$140,500.00

CONTACT INFORMATION

JOE & MARGE ALLAN
81 RIDGE DRIVE
PROVIDENCE, RI  02813
1-555-231-2135
#+END_SRC

* Winding path

It's a maze, but the bad paths have been blocked off. Mark the correct path.
** Start file
#+BEGIN_SRC 
|||||x|||||||
|   |   |   |
| | ||| | | |
| | | | | | |
| | | | | | |
| |   |   | |
||||||||||| |
|       |   |
| ||||| | |||
| |   |   | |
| ||||||||| |
|       |   |
|||||||x|||||
#+END_SRC

** End file
#+BEGIN_SRC 
|||||x|||||||
|   |xxx|xxx|
| | |||x|x|x|
| | | |x|x|x|
| | | |x|x|x|
| |   |xxx|x|
|||||||||||x|
|xxxxxxx|xxx|
|x|||||x|x|||
|x|   |xxx| |
|x||||||||| |
|xxxxxxx|   |
|||||||x|||||
#+END_SRC

* Circle in a square

Probably looks more like "Egg in a rectangle" in most fonts, but it's actually 23x23.
** Start file
#+BEGIN_SRC 
#######
###########
###############
#################
###################
###################
#####################
#####################
#######################
#######################
#######################
#######################
#######################
#######################
#######################
#####################
#####################
###################
###################
#################
###############
###########
#######
#+END_SRC

** End file
#+BEGIN_SRC 
........#######........
......###########......
....###############....
...#################...
..###################..
..###################..
.#####################.
.#####################.
#######################
#######################
#######################
#######################
#######################
#######################
#######################
.#####################.
.#####################.
..###################..
..###################..
...#################...
....###############....
......###########......
........#######........
#+END_SRC

* 42-header

Rush 42mexican-standoff at 42 school
** Start file
#+BEGIN_SRC 
void    read_loop(char *delim_string, char **ptr, int op, char **doc)
{
        while(**ptr)
        {
                char    *tmp;
                char    *tmp2;

                tmp = *ptr;
                while (**ptr && **ptr != '\n')
                        (*ptr)++;
                if (**ptr == '\n')
                        (*ptr)++;
                tmp = ft_strndup(tmp, *ptr - tmp);
                if (op == DLESSDASH)
                        tmp = remove_tab(tmp);
                if (!ft_strcmp(delim_string, tmp))
                        break;
        tmp2 = ft_strjoin(*doc, tmp);
                free(*doc);
                free(tmp);           
                *doc = tmp2;
        }
}
#+END_SRC

** End file
#+BEGIN_SRC 
void    read_loop(char *delim_string, char **ptr, int op, char **doc)
{
        char    *tmp;
        char    *tmp2;

        while (**ptr)
        {
                tmp = *ptr;
                while (**ptr && **ptr != '\n')
                        (*ptr)++;
                if (**ptr == '\n')
                        (*ptr)++;
                tmp = ft_strndup(tmp, *ptr - tmp);
                if (op == DLESSDASH)
                        tmp = remove_tab(tmp);
                if (!ft_strcmp(delim_string, tmp))
                        break ;
                tmp2 = ft_strjoin(*doc, tmp);
                free(*doc);
                free(tmp);
                *doc = tmp2;
        }
}
#+END_SRC

* Create a pandoc compatible table

In [this vimcast][1], a featured gist from Tim Pope shows how to quickly make a simple table structure. How fast can you convert it to pandoc's markdown style? [1]: http://vimcasts.org/episodes/aligning-text-with-tabular-vim/
** Start file
#+BEGIN_SRC 
| This  | Is    | A Table   | Example     |
| I'm   | going | to        | fill        |
| it    | with  | random    | information |
| just  | to    | save      | me          |
| time. | In    | the       | spirit      |
| of    | vim   | I         | am          |
| quite | often | extremely | lazy.       |
#+END_SRC

** End file
#+BEGIN_SRC 
This   Is     A Table    Example
-----  -----  ---------  -----------
I'm    going  to         fill
it     with   random     information
just   to     save       me
time.  In     the        spirit
of     vim    I          am
quite  often  extremely  lazy.
#+END_SRC

* Almost encrypted

Convert the first paragraph to be even less readable.
** Start file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, consectetur magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.  Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.  Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
#+END_SRC

** End file
#+BEGIN_SRC 
Yberz vcfhz qbybe fvg nzrg, pbafrpgrghe zntan nyvdhn. Hg ravz nq zvavz iravnz,
dhvf abfgehq rkrepvgngvba hyynzpb ynobevf avfv hg nyvdhvc rk rn pbzzbqb
pbafrdhng. Qhvf nhgr veher qbybe va erceruraqrevg va ibyhcgngr iryvg rffr
pvyyhz qbyber rh shtvng ahyyn cnevnghe.  Rkprcgrhe fvag bppnrpng phcvqngng aba
cebvqrag, fhag va phycn dhv bssvpvn qrfrehag zbyyvg navz vq rfg ynobehz.

Lorem ipsum dolor sit amet, consectetur magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.  Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
#+END_SRC

* Convert pandoc unordered list to a numbered list

I know it's possible to use #. in pandoc to auto-generate numbered lists, but then it's not easy to tell how many items there are when reading it in Markdown. How fast can you make the switch?
** Start file
#+BEGIN_SRC 
My cursor happens to be on this line

## Here is my unordered list
   * item 1
      + it has some sub-items
         - sometimes it has sub-sub-items
      - i list some information about it
   * here is another item
   * and another
      - with some random sub-item
      - maybe with something in **bold** to make asterisks suck
   * woohoo I'm listing stuff like mad
   * I'm a mad pandoc'ing fool
      - long-live **John MacFarlane**!
      + reasons why pandoc is awesome
         - there's just too many list
         - but i'll put some more sub-sub-items for example
         - superfluous - and + to make matching them a pain
   * woo look at these sexy bullet points
   * you almost don't want to turn them into integers
   * but then you do because you know it's the right thing to do

## Here's some other stuff in the file
   * blah blah blah
   * maybe I should go with #. but then it's not readable in txt format
#+END_SRC

** End file
#+BEGIN_SRC 
My cursor happens to be on this line

## Here is my unordered list
   1. item 1
      + it has some sub-items
         - sometimes it has sub-sub-items
      - i list some information about it
   2. here is another item
   3. and another
      - with some random sub-item
      - maybe with something in **bold** to make asterisks suck
   4. woohoo I'm listing stuff like mad
   5. I'm a mad pandoc'ing fool
      - long-live **John MacFarlane**!
      + reasons why pandoc is awesome
         - there's just too many list
         - but i'll put some more sub-sub-items for example
         - superfluous - and + to make matching them a pain
   6. woo look at these sexy bullet points
   7. you almost don't want to turn them into integers
   8. but then you do because you know it's the right thing to do

## Here's some other stuff in the file
   * blah blah blah
   * maybe I should go with #. but then it's not readable in txt format
#+END_SRC

* Solve the Sokoban

A wink for all Vimgolfers that play Nethack too.
** Start file
#+BEGIN_SRC 
-------- ------
|<|@...---....|
|^|-.00....0..|
|^||..00|.0.0.|
|^||....|.....|
|^|------0----|
|^|    |......|
|^------......|
|..^^^^0000...|
|??-----......|
----   --------
#+END_SRC

** End file
#+BEGIN_SRC 
-------- ------
|@|>...---....|
|.|-..........|
|.||..00|.....|
|.||....|.....|
|.|------.----|
|.|    |......|
|.------......|
|.............|
|..-----......|
----   --------
#+END_SRC

* SFD-ROC: Tic-Tac-Toe

Tic-Tac-Toe You are 'X', and it is your turn. Stop 'O' from winning, and complete the game. Draw a diagonal line through your winning row of three X's.
** Start file
#+BEGIN_SRC 
Tic-Tac-Toe
You are 'X', and it is your turn. Stop 'O' from winning, and complete the game.

        |   |
      X | O |
        |   |
     -----------
        |   |
        |   |
        |   |
     -----------
        |   |
        | O | X
        |   |


Bonus: Draw a diagonal line through your winning row of three X's.
#+END_SRC

** End file
#+BEGIN_SRC 
Tic-Tac-Toe
You are 'X', and it is your turn. Stop 'O' from winning, and complete the game.

     \  |   |
      X | O |
       \|   |
     -----------
        |\  |
        | X |
        |  \|
     -----------
        |   |\
        | O | X
        |   |  \


Bonus: Draw a diagonal line through your winning row of three X's.
#+END_SRC

* Entries sort

It cames to my mind a weird idea : sorting parts of my .vimrc. Take few minutes to sort out this, it's easy !
** Start file
#+BEGIN_SRC 
set ai                                          " set auto-indenting on for programming
syntax on                                       " turn syntax highlighting on by default
set undolevels=100
set backup backupdir=/tmp                       " swap files. (/tmp/file~)
                                                " (see also 'set writebackup' and 'set backupskip')
iab _file <C-R>%                                " filename (register %)
autocmd! BufWritePost $MYVIMRC source $MYVIMRC  " auto-reload when ~/.vimrc is edited
                                                " MYVIMRC is the platform-independent location
                                                " of your .vimrc file
#+END_SRC

** End file
#+BEGIN_SRC 
autocmd! BufWritePost $MYVIMRC source $MYVIMRC  " auto-reload when ~/.vimrc is edited
                                                " MYVIMRC is the platform-independent location
                                                " of your .vimrc file
iab _file <C-R>%                                " filename (register %)
set ai                                          " set auto-indenting on for programming
set backup backupdir=/tmp                       " swap files. (/tmp/file~)
                                                " (see also 'set writebackup' and 'set backupskip')
set undolevels=100
syntax on                                       " turn syntax highlighting on by default
#+END_SRC

* PEP8 Python Wrapping Comments and Code

According to PEP8, long flowy text and code should have different max line lengths. Code: 79 characters max Long flowy text: 72 characters max
** Start file
#+BEGIN_SRC 
class Rectangle(Blob):
    """
    According to PEP8: [P]lease limit all lines to a maximum of 79 characters. For flowing long blocks of text, limiting the length to 72 characters is recommended. 

    This comment should have a max line width of 72. Note: (68 + 4 spaces for indent = 72)
    """

    # Below code should have a max line width of 79
    def __init__(self, width, height, color='black', emphasis=None, highlight=0):
        Blob.__init__(self, width, height, color, emphasis, highlight)
#+END_SRC

** End file
#+BEGIN_SRC 
class Rectangle(Blob):
    """
    According to PEP8: [P]lease limit all lines to a maximum of 79
    characters. For flowing long blocks of text, limiting the length to
    72 characters is recommended. 

    This comment should have a max line width of 72. Note: (68 + 4
    spaces for indent = 72)
    """

    # Below code should have a max line width of 79
    def __init__(self, width, height, color='black', emphasis=None,
                 highlight=0):
        Blob.__init__(self, width, height, color, emphasis, highlight)
#+END_SRC

* O Christmas Tree

Design a macro that makes trees grow (or ASCII triangles, if that's too hard).
** Start file
#+BEGIN_SRC 
^
#+END_SRC

** End file
#+BEGIN_SRC 
^

 ^
^^^

  ^
 ^^^
^^^^^

   ^
  ^^^
 ^^^^^
^^^^^^^

    ^
   ^^^
  ^^^^^
 ^^^^^^^
^^^^^^^^^
#+END_SRC

* Sort yaml structures alphabetically by root key names

sometimes we want to sort structures alphabetically in yaml files
** Start file
#+BEGIN_SRC 
c:
  required: false

h:
  optional: true
  choice:
    - true
    - false

f:
  required: true

e:
  optional: true
  choice:
    - b
    - a

g:
  optional: false

j:
  required: true

a:
  required: true

i:
  required: false

d:
  required: false

b:
  optional: true
  choice:
    - 1
    - 2
#+END_SRC

** End file
#+BEGIN_SRC 
a:
  required: true

b:
  optional: true
  choice:
    - 1
    - 2

c:
  required: false

d:
  required: false

e:
  optional: true
  choice:
    - b
    - a

f:
  required: true

g:
  optional: false

h:
  optional: true
  choice:
    - true
    - false

i:
  required: false

j:
  required: true
#+END_SRC

* Draw the Go board

which is a 19×19 lines board. Here we use ascii characters only for simplicity. See diff file to get a sense. (See also http://en.wikipedia.org/wiki/Go_(game))
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
W t t t t t t t t t t t t t t t t t X 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . + . . . . . + . . . . . + . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . + . . . . . + . . . . . + . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
l . . + . . . . . + . . . . . + . . r 
l . . . . . . . . . . . . . . . . . r 
l . . . . . . . . . . . . . . . . . r 
Y b b b b b b b b b b b b b b b b b Z 
#+END_SRC

* Define to require

When JSHint is enabled, there's a rule that doesn't let you have more than 6 arguments in a function, so the moment you need to add a 7th argument, you need to do a refactoring.
** Start file
#+BEGIN_SRC 
define(
    [
        'jquery',
        'underscore',
        'json',
        'benchmark',
        'coffee',
        'beans',
        'hello'
    ],
    function($, _, json, benchmark, coffee, beans, hello) {
    });
#+END_SRC

** End file
#+BEGIN_SRC 
define(function(require) {
    var $ = require('jquery');
    var _ = require('underscore');
    var json = require('json');
    var benchmark = require('benchmark');
    var coffee = require('coffee');
    var beans = require('beans');
    var hello = require('hello');
});
#+END_SRC

* Refactoring useless Method away

Real-life challenge, convert a bunch of ifs to a switch statement
** Start file
#+BEGIN_SRC 
if (isTyp(YBD.Typ_GEBAEUDE, currentTyp)) {
        immobilienItem.setGebaeudeNr(currentItem.getGebaeudeNr());
}
if (isTyp(YBD.Typ_OBJEKT, currentTyp)) {
        immobilienItem.setObjektNr(currentItem.getObjektNr());
}
if (isTyp(YBD.Typ_ETAGE, currentTyp)) {
        immobilienItem.setEtageNr(currentItem.getEtageNr());
}
if (isTyp(YBD.Typ_IMMOBILIE, currentTyp)) {
        immobilienItem.setImmobilieNr(currentItem.getImmobilieNr());
}
if (isTyp(YBD.Typ_HAUS, currentTyp)) {
        immobilienItem.setHausNr(currentItem.getHausNr());
}
#+END_SRC

** End file
#+BEGIN_SRC 
switch (currentTyp) {
        case YBD.Typ_GEBAEUDE:
                immobilienItem.setGebaeudeNr(currentItem.getGebaeudeNr());
                break;
        case YBD.Typ_OBJEKT:
                immobilienItem.setObjektNr(currentItem.getObjektNr());
                break;
        case YBD.Typ_ETAGE:
                immobilienItem.setEtageNr(currentItem.getEtageNr());
                break;
        case YBD.Typ_IMMOBILIE:
                immobilienItem.setImmobilieNr(currentItem.getImmobilieNr());
                break;
        case YBD.Typ_HAUS:
                immobilienItem.setHausNr(currentItem.getHausNr());
                break;
}
#+END_SRC

* Turn a ninja to case-insensitive...
Turn a ninja to case-insensitive [Nn][Ii][Nn][Jj][Aa] regexp!

I bumped into this in a dailywtf code: http://pastebin.com/QApa5ycS I didn't want to translate a string whenever I wanted to be [Ss][Aa][Rr][Cc][Aa][Ss][Tt][Ii][Cc] on slack, so I figured a script (python, sed, whatever) would be helpful. Well, or a few vim keystroke!
** Start file
#+BEGIN_SRC 
SarCastic
#+END_SRC

** End file
#+BEGIN_SRC 
[Ss][Aa][Rr][Cc][Aa][Ss][Tt][Ii][Cc]
#+END_SRC

* CSV to JSON

A search for shortest vimissh way to convert CSV to JSON.
** Start file
#+BEGIN_SRC 
Year,Make,Model,Length
1997,Ford,E350,2.34
2000,Mercury,Cougar,2.38
#+END_SRC

** End file
#+BEGIN_SRC 
[
        {
                "Year": "1997",
                "Make": "Ford",
                "Model": "E350",
                "Length": "2.34"
        },
        {
                "Year": "2000",
                "Make": "Mercury",
                "Model": "Cougar",
                "Length": "2.38"
        }
]
#+END_SRC

* Getters & Setters: Java

Boilerplate getters & setters - it's a tedious fact of life in Java, and probably the only thing that still pulls me back to an IDE. Perhaps someone knows a fast, pure vim way...
** Start file
#+BEGIN_SRC 
package com.vimgolf.challenge;

public class Person {
        private String firstName;
        private String surname;
        private Integer age;
}
#+END_SRC

** End file
#+BEGIN_SRC 
package com.vimgolf.challenge;

public class Person {
        private String firstName;
        private String surname;
        private Integer age;

        public String getFirstName() { return firstName; }
        public void setFirstName( String firstName ) {
                this.firstName = firstName;
        }

        public String getSurname() { return surname; }
        public void setSurname( String surname ) {
                this.surname = surname;
        }

        public Integer getAge() { return age; }
        public void setAge( Integer age ) {
                this.age = age;
        }
}
#+END_SRC

* Fill visual area

Just have fun!
** Start file
#+BEGIN_SRC 
vim: set nrformats=alpha:
----------
----------
----------
----------
----------
----------
----------
----------
----------
----------
#+END_SRC

** End file
#+BEGIN_SRC 
vim: set nrformats=alpha:
jihgfedcba
iihgfedcba
hhhgfedcba
ggggfedcba
fffffedcba
eeeeeedcba
dddddddcba
ccccccccba
bbbbbbbbba
aaaaaaaaaa
#+END_SRC

* Overall Vimgolf Rank

Suppose you are trying to figure out what your overall rank is at Vimgolf(the sum of all the ranks you got), and as a Vim ninja you decided to use Vim to do the job. Your solution should work for every Vimgolf profile page(The actual input file for this challenge is my Vimgolf profile page). So, direct answer insertion is considered cheating.
** Start file
#+BEGIN_SRC 
Generate Fibonacci Numbers - Rank: 1/66, Score: 20
Use your super vim powers to generate Fibonacci Numbers.

Remove Accent off the Letter - Rank: 1/49, Score: 38
Remove all the accent from extremely accented statements.

Remember FizzBuzz? - Rank: 1/118, Score: 53
Output FizzBuzz to 100. Start with nothing.

Whitespace, empty lines and tabs - Rank: 1/257, Score: 15
Convert tabs to spaces, strip empty lines and trailing whitespace.

Before there was Farmville... - Rank: 1/22, Score: 165
There was old MacDonald. For my toddler. The first Vim sing-a-long?

Another Mixed-Up Haiku - Rank: 1/82, Score: 21
VimGolf ... a perfect evening?

Assignment Alignment - Rank: 1/66, Score: 18
line up the operators. Use spaces, not tabs.

fix typos, reformat and refactor an ActiveRecord model. - Rank: 1/35, Score: 105
Simple case of refactoring ruby code, change camelize word to undescored (vice versa), proper indentation, removing trailing white spaces, etc.

Promote that perl 'one-liner' ... - Rank: 1/19, Score: 97
You've just sorted your data using perl -e, when suddenly you have to add a row and do it again. That's twice - you'll almost certainly do it again. Time to turn it into a real script. We'll start from having pasted it in ...

Align it, win it. - Rank: 1/70, Score: 32
Align this simple listing.

Getters & Setters: Java - Rank: 1/47, Score: 92
Boilerplate getters & setters - it's a tedious fact of life in Java, and probably the only thing that still pulls me back to an IDE. Perhaps someone knows a fast, pure vim way...

CSV to JSON - Rank: 2/65, Score: 60
A search for shortest vimissh way to convert CSV to JSON.

Round Round - Rank: 2/71, Score: 23
Round Round

Prime Numbers - Rank: 2/54, Score: 43
List the first 100 prime numbers.

Here, piggy, piggy... - Rank: 2/35, Score: 77
Youay owknay atwhay otay oday...

82 bottles of beer on the wall - Rank: 2/128, Score: 109
Take them down. (sorry, only 82 bottles because the problem size is limited!)

Reformat most common surnames - Rank: 2/132, Score: 25
Reformat copy-pasted table into a list of the most common surnames

Return the cow - Rank: 2/41, Score: 41
This cow is too verbose. Give it a lesson.

Table Reshuffle - Rank: 2/103, Score: 24
Fix the column order in this table... also append the new 'username' column.

Make Vim ASCII Art - Rank: 2/14, Score: 139
Art is the triumph over chaos. ~John Cheever

It'ss tooo coold too typpe todaay - Rank: 3/75, Score: 16
My hands are numb with cold. It's hard to type correctly.

Reverse Simple Deletion - Rank: 3/248, Score: 12
You did the simple deletion, now reverse it.

Cartesian product - Rank: 3/74, Score: 26
{1,2,3,4,5} X {1,2,3,4,5}

Braces or Brackets? - Rank: 3/125, Score: 34
Someone forgot whether to use braces or brackets and you have to clean up their code!

Insert a Markdown link - Rank: 3/120, Score: 23
Put a link in a markdown document, using the after-the-paragraph format.

Dumb to smart - Rank: 3/41, Score: 29
Turn dumb quote to smart vim's way.

Deleting folded text - Rank: 3/78, Score: 19
The text below contains three folds. Delete them (and the text inside them). For example: 123 456 /*{{{*/ 789 /*}}}*/ 012 Should become: 123 012 Also, add `aoeuaoeu` to make sure small solutions don't get flagged as cheating.

Add fold markers to a .c file - Rank: 3/65, Score: 30
Fold markers can make it easier to navigate source code. Add them to this .c file.

Linear congruential generator - Rank: 3/46, Score: 30
http://en.wikipedia.org/wiki/Linear_congruential_generator

Sorting paragraphs - Rank: 3/142, Score: 21
Order the paragraphs correctly, per prefixed index

Generate English Alphabets - Rank: 4/101, Score: 24
Start with a, get up to z.

Ruby 1.9 hashes - Rank: 4/227, Score: 12
Rubyists talk about being cutting edge but how many are using 1.9 in production? Time to convert those verbose 1.8 hashes in to symbolic, succinct 1.9 beauties!

Turn this csv list into queries - Rank: 4/93, Score: 106
Transform each line of this csv file into a MySQL-ready INSERT query.

Word Blender - Rank: 4/48, Score: 34
The insides of long words seem to have been run through the blender. Can you fix this famous tale, brave knight?

Happy New Year! - Rank: 4/48, Score: 24
This is a simple new year's challenge.

Flodder-challenge - Rank: 5/150, Score: 28
Replace the text the most efficient and win!

A Simple One - Rank: 5/356, Score: 9
Here is a very simple one - just to illustrate/introduce a vim feature that some people seem to miss...

Hatsuyume - Rank: 5/163, Score: 15
http://en.wikipedia.org/wiki/Hatsuyume

Reverse a single line - Rank: 5/218, Score: 9
Reverse a single line vertically.

The Universal Declaration of Human Rights, Article 1 - Rank: 5/40, Score: 24
Somebody's got this slightly muddled up. See how quickly you can fix it. (I made this to experiment with buffers. I'm not actually sure whether this is faster with buffers or without.)

Letters are numbers - Rank: 5/55, Score: 26
Letters and numbers are interchangeable. A lot of programming languages give you simple ways to convert individual letters to hex, binary and decimal but does Vim?

Reformat some Python - Rank: 6/191, Score: 34
Fix some very bizarrely laid-out code.

Fix the Haiku - Rank: 6/72, Score: 33
Change this slightly scrambled haiku to its unscrambled form and fix the capitalisation and punctuation along the way.

Solve the Sokoban - Rank: 6/60, Score: 30
A wink for all Vimgolfers that play Nethack too.

Reformat a C golf submission - Rank: 7/165, Score: 22
Take this C golf submission (for the "tiny but standards-compliant Hello World program" category, naturally), and turn it into formatted C code.

PEP8 Python Wrapping Comments and Code - Rank: 7/53, Score: 26
According to PEP8, long flowy text and code should have different max line lengths. Code: 79 characters max Long flowy text: 72 characters max

Shebangs for all - Rank: 7/270, Score: 12
We've all seen or used a shebang once or twice. Ditch the specific paths and leave just a dynamic Ruby and Python bath behind.

Simple deletion - Rank: 7/375, Score: 6
Try this simple deletion. People using other text editor can achieve this in less than 30 keystroke you are using vim.

Compile C - Rank: 8/187, Score: 11
You might have to get clever to do this one.

Reconstruct the Sentence - Rank: 9/235, Score: 20
Get the sentence back in the proper order, remove duplicate lines, and then combine the separate lines into one.

Vim manuals written by Bram. - Rank: 9/27, Score: 52
Find Vim reference manuals written by Bram Moolenaar.

Ruby 1.9 compat - Rank: 10/224, Score: 14
Remember when Ruby supported `when <expr> :`? Well, it doesn't in 1.9, so let's make sure we use `then`, without ruining our lovely new hash syntax!

Reformat long lines - Rank: 13/62, Score: 17
Rearrange this ruby method call to put each parameter on its own line. Could become a useful macro.

Python Hello World! Reformatting - Rank: 14/294, Score: 41
A novice Python using prints Hello World! and a pro shows him different way. Using vim to get into pro style from novice, win the challenge.

Indentation - Rank: 14/189, Score: 23
Indent each line according to the right number of spaces it needs.

Reverse and count - Rank: 15/197, Score: 23
Someone typed things upside down and now a Vim ninja needs to reverse the lines and count how many there are.

The holy-grail may help - Rank: 15/117, Score: 16
Can you find it in less than 20 strokes, Arthur?

Wrap the text of an email message to 79 characters - Rank: 17/156, Score: 5
You're replying to an email with silly long lines. Clean them up.

Almost encrypted - Rank: 18/77, Score: 5
Convert the first paragraph to be even less readable.

Reformat/Refactor a Golfer Class - Rank: 18/587, Score: 32
A simple case of removing unneeded code and fixing broken indentation.

Change the content of a string - Rank: 21/267, Score: 22
This docstring is a complete lie. Fix it.

Make Fancy Header - Rank: 23/323, Score: 16
Make the header text stand out with surrounding asterisks

Reverse characters in a line - Rank: 24/273, Score: 8
You have everything you need, just not in the right order. Mastermind would give you 26 white pegs.

Context insensitive completion 0 - Rank: 26/170, Score: 7
Buried in the lines you're not supposed to add is the line "Add this line!" Add that line to the top of the file.

Ruby blocks - Rank: 26/143, Score: 13
Lots of lines fill up my hard drive. Let's use curly braces.

The Cake is a Lie - Rank: 28/348, Score: 9
Correct the capitalization of each word

Do you have a big gun? - Rank: 33/78, Score: 5
Of course I have.

Increment, increment, increment.... - Rank: 39/169, Score: 12
Vim likes macros

Sort and add attributes - Rank: 39/347, Score: 33
Sort the states and add the attribute country to each record.

Get rid of html tags - Rank: 39/163, Score: 17
Want to read more about Vim's background? Then get rid of those html tags...

Context Insensitive completion 1 - Rank: 45/187, Score: 18
Finish writing this simple Python HTTP server.

Simple text editing with Vim - Rank: 66/857, Score: 14
Make the pairs of lines match up by making each second line same as first

Search and Replace 0 - Rank: 70/745, Score: 12
Replace every instance of 'aaa' with 'xaaax'.
#+END_SRC

** End file
#+BEGIN_SRC 
794
#+END_SRC

* Write Setters and Getters for PHP

Just simple automation of writing Setters and Getters like Doctrine might use.
** Start file
#+BEGIN_SRC 
<?php
class Example {

        firstProperty
        secondItem
        lastAttribute
}
#+END_SRC

** End file
#+BEGIN_SRC 
<?php
class Example {

        private $firstProperty;

        public function getFirstProperty()
        {
                return $this->firstProperty;
        }

        public function setFirstProperty($value)
        {
                $this->firstProperty = $value;
        }

        private $secondItem;

        public function getSecondItem()
        {
                return $this->secondItem;
        }

        public function setSecondItem($value)
        {
                $this->secondItem = $value;
        }

        private $lastAttribute;

        public function getLastAttribute()
        {
                return $this->lastAttribute;
        }

        public function setLastAttribute($value)
        {
                $this->lastAttribute = $value;
        }
}
#+END_SRC

* Checkerboard case pattern

All the squares are white. Make some of them black. But only the right ones.
** Start file
#+BEGIN_SRC 
aaaaaaaa
aaaaaaaa
aaaaaaaa
aaaaaaaa
aaaaaaaa
aaaaaaaa
aaaaaaaa
aaaaaaaa
#+END_SRC

** End file
#+BEGIN_SRC 
aAaAaAaA
AaAaAaAa
aAaAaAaA
AaAaAaAa
aAaAaAaA
AaAaAaAa
aAaAaAaA
AaAaAaAa
#+END_SRC

* Changing URL path in CSS

What's the quickest way to swap out all the URLs in a CSS file? Is it wasted keystrokes using look-behinds and look-aheads? (I'm sorry for the delete/report--I made a mistake with the last one requiring an ugly search for graphic to replace with images. I just intended this to be a simple search and replace that might possibly generate some macros or normals solutions that are quicker)
** Start file
#+BEGIN_SRC 
body {
        background: #d47300 url(graphics/noise.png);    
        font-family: 'Open Sans', sans-serif;
}


.background {
        background: url(../images/background_shadow.png) no-repeat top center;
        background-position: 50% 16%;   
}

.background_overlay {
        background: url(../images/background_overlay.png) no-repeat top center;
        padding: 0;
        margin:0;
}


.order {
        background: #ff9e00 url(graphics/order.png) repeat-x;
        height: 25px;
        display: inline-block;
        color: #d47300;
        line-height: 25px;
        font-weight: 700;
        font-size: 13px;
        font-weight: 800;
        padding: 0 10px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
        text-transform: uppercase;
        color: #825600;
        text-shadow: 0px 1px 0px rgba(255,255,255,0.50);
}

.sponsor:hover {
        background-position: 0px -25px;
}

.sponsor:active {
        background: #ff9e00 url(../images/sponsors/sponsorBlock.png) repeat-x;
        background-position: 0px -50px;
}


.telephone {
        background: #fff url(graphics/telephone.png) repeat-x;
        height: 25px;
        display: inline-block;
        color: #A65A01;
        line-height: 25px;
        font-weight: 700;
        font-size: 14px;
        padding: 0 10px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
        text-shadow: 0px 1px 0px rgba(255,255,255,0.50);
}


.social {
        background: #fff url(../social/telephone.png) repeat-x;
        display: inline-block;
        height: 25px;
        line-height: 25px;
        padding: 0 10px;
        color: #A65A01;
        font-weight: 700;
        font-size: 14px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
}
#+END_SRC

** End file
#+BEGIN_SRC 
body {
        background: #d47300 url(/wp-content/themes/black/graphics/noise.png);   
        font-family: 'Open Sans', sans-serif;
}


.background {
        background: url(/wp-content/themes/black/images/background_shadow.png) no-repeat top center;
        background-position: 50% 16%;   
}

.background_overlay {
        background: url(/wp-content/themes/black/images/background_overlay.png) no-repeat top center;
        padding: 0;
        margin:0;
}


.order {
        background: #ff9e00 url(/wp-content/themes/black/graphics/order.png) repeat-x;
        height: 25px;
        display: inline-block;
        color: #d47300;
        line-height: 25px;
        font-weight: 700;
        font-size: 13px;
        font-weight: 800;
        padding: 0 10px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
        text-transform: uppercase;
        color: #825600;
        text-shadow: 0px 1px 0px rgba(255,255,255,0.50);
}

.sponsor:hover {
        background-position: 0px -25px;
}

.sponsor:active {
        background: #ff9e00 url(/wp-content/themes/black/images/sponsors/sponsorBlock.png) repeat-x;
        background-position: 0px -50px;
}


.telephone {
        background: #fff url(/wp-content/themes/black/graphics/telephone.png) repeat-x;
        height: 25px;
        display: inline-block;
        color: #A65A01;
        line-height: 25px;
        font-weight: 700;
        font-size: 14px;
        padding: 0 10px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
        text-shadow: 0px 1px 0px rgba(255,255,255,0.50);
}


.social {
        background: #fff url(/wp-content/themes/black/social/telephone.png) repeat-x;
        display: inline-block;
        height: 25px;
        line-height: 25px;
        padding: 0 10px;
        color: #A65A01;
        font-weight: 700;
        font-size: 14px;
        -webkit-border-radius: 20px;
        -moz-border-radius: 20px;
        box-shadow: 0 0 0px 5px rgba(0,0,0,0.10);       
        margin-right: 20px;
}
#+END_SRC

* Extract text from xml

Extract text from xml file (ignoring commented out elements) and create a one line regex.
** Start file
#+BEGIN_SRC 
<list>
  <item>txt123</item>
  <!-- <item>txt124</item> -->
  <!-- <item>txt126</item> -->
  <item>txt127</item>
  <item>txt137</item>
  <!-- <item>txt145</item> -->
  <item>txt148</item>
  <!-- <item>txt150</item> -->
</list>
#+END_SRC

** End file
#+BEGIN_SRC 
^(txt123|txt127|txt137|txt148).*$
#+END_SRC

* Happy New Year!

This is a simple new year's challenge.
** Start file
#+BEGIN_SRC 
Happy New Year!
#+END_SRC

** End file
#+BEGIN_SRC 
<H>  72,  Hex 48,  Octal 110
<a>  97,  Hex 61,  Octal 141
<p>  112,  Hex 70,  Octal 160
<p>  112,  Hex 70,  Octal 160
<y>  121,  Hex 79,  Octal 171
< >  32,  Hex 20,  Octal 040
<N>  78,  Hex 4e,  Octal 116
<e>  101,  Hex 65,  Octal 145
<w>  119,  Hex 77,  Octal 167
< >  32,  Hex 20,  Octal 040
<Y>  89,  Hex 59,  Octal 131
<e>  101,  Hex 65,  Octal 145
<a>  97,  Hex 61,  Octal 141
<r>  114,  Hex 72,  Octal 162
<!>  33,  Hex 21,  Octal 041
#+END_SRC

* Complete the hex array data (Part II)

Do not use external tools(e.g. tac, seq) [My interpretation of Rule #7]
** Start file
#+BEGIN_SRC 
unsigned int hex[] = {
        0x00,
};
#+END_SRC

** End file
#+BEGIN_SRC 
unsigned int hex[] = {
        0x00, 0x01, 0x02, 0x03, 0x04, 0x05, 0x06, 0x07,
        0x08, 0x09, 0x0a, 0x0b, 0x0c, 0x0d, 0x0e, 0x0f,
        0x10, 0x11, 0x12, 0x13, 0x14, 0x15, 0x16, 0x17,
        0x18, 0x19, 0x1a, 0x1b, 0x1c, 0x1d, 0x1e, 0x1f,
        0x20, 0x21, 0x22, 0x23, 0x24, 0x25, 0x26, 0x27,
        0x28, 0x29, 0x2a, 0x2b, 0x2c, 0x2d, 0x2e, 0x2f,
        0x30, 0x31, 0x32, 0x33, 0x34, 0x35, 0x36, 0x37,
        0x38, 0x39, 0x3a, 0x3b, 0x3c, 0x3d, 0x3e, 0x3f,
        0x40, 0x41, 0x42, 0x43, 0x44, 0x45, 0x46, 0x47,
        0x48, 0x49, 0x4a, 0x4b, 0x4c, 0x4d, 0x4e, 0x4f,
        0x50, 0x51, 0x52, 0x53, 0x54, 0x55, 0x56, 0x57,
        0x58, 0x59, 0x5a, 0x5b, 0x5c, 0x5d, 0x5e, 0x5f,
        0x60, 0x61, 0x62, 0x63, 0x64, 0x65, 0x66, 0x67,
        0x68, 0x69, 0x6a, 0x6b, 0x6c, 0x6d, 0x6e, 0x6f,
        0x70, 0x71, 0x72, 0x73, 0x74, 0x75, 0x76, 0x77,
        0x78, 0x79, 0x7a, 0x7b, 0x7c, 0x7d, 0x7e, 0x7f,
        0x80, 0x81, 0x82, 0x83, 0x84, 0x85, 0x86, 0x87,
        0x88, 0x89, 0x8a, 0x8b, 0x8c, 0x8d, 0x8e, 0x8f,
        0x90, 0x91, 0x92, 0x93, 0x94, 0x95, 0x96, 0x97,
        0x98, 0x99, 0x9a, 0x9b, 0x9c, 0x9d, 0x9e, 0x9f,
        0xa0, 0xa1, 0xa2, 0xa3, 0xa4, 0xa5, 0xa6, 0xa7,
        0xa8, 0xa9, 0xaa, 0xab, 0xac, 0xad, 0xae, 0xaf,
        0xb0, 0xb1, 0xb2, 0xb3, 0xb4, 0xb5, 0xb6, 0xb7,
        0xb8, 0xb9, 0xba, 0xbb, 0xbc, 0xbd, 0xbe, 0xbf,
        0xc0, 0xc1, 0xc2, 0xc3, 0xc4, 0xc5, 0xc6, 0xc7,
        0xc8, 0xc9, 0xca, 0xcb, 0xcc, 0xcd, 0xce, 0xcf,
        0xd0, 0xd1, 0xd2, 0xd3, 0xd4, 0xd5, 0xd6, 0xd7,
        0xd8, 0xd9, 0xda, 0xdb, 0xdc, 0xdd, 0xde, 0xdf,
        0xe0, 0xe1, 0xe2, 0xe3, 0xe4, 0xe5, 0xe6, 0xe7,
        0xe8, 0xe9, 0xea, 0xeb, 0xec, 0xed, 0xee, 0xef,
        0xf0, 0xf1, 0xf2, 0xf3, 0xf4, 0xf5, 0xf6, 0xf7,
        0xf8, 0xf9, 0xfa, 0xfb, 0xfc, 0xfd, 0xfe, 0xff,
};
#+END_SRC

* The Universal Declaration of Human Rights, Article 1

Somebody's got this slightly muddled up. See how quickly you can fix it. (I made this to experiment with buffers. I'm not actually sure whether this is faster with buffers or without.)
** Start file
#+BEGIN_SRC 
All in a spirit of human beings are equal in dignity and rights.
They are born free and should act
towards one another endowed with reason and conscience and brotherhood.
#+END_SRC

** End file
#+BEGIN_SRC 
All human beings are born free and equal in dignity and rights.
They are endowed with reason and conscience and should act
towards one another in a spirit of brotherhood.
#+END_SRC

* Rail fence transposition cipher

Solve a rail fence transposition cipher using vim. This ciphertext was created using two rails. Use vim to transpose the text and recover the original quote.
** Start file
#+BEGIN_SRC 
TeesfothfseadoeoeflowlbBueehlsefrteatrnmrpwruyuilercLe
#+END_SRC

** End file
#+BEGIN_SRC 
ThelesseffortthefasterandmorepowerfulyouwillbeBruceLee
#+END_SRC

* Sudoku table

Make this simple sudoku table look nice and legible.
** Start file
#+BEGIN_SRC 
536917284
287543691
419286357
621798435
358124976
974635812
142879563
863451729
795362148
#+END_SRC

** End file
#+BEGIN_SRC 
   - - -   - - -   - - -
 | 5 3 6 | 9 1 7 | 2 8 4 |
 | 2 8 7 | 5 4 3 | 6 9 1 |
 | 4 1 9 | 2 8 6 | 3 5 7 |
   - - -   - - -   - - -
 | 6 2 1 | 7 9 8 | 4 3 5 |
 | 3 5 8 | 1 2 4 | 9 7 6 |
 | 9 7 4 | 6 3 5 | 8 1 2 |
   - - -   - - -   - - -
 | 1 4 2 | 8 7 9 | 5 6 3 |
 | 8 6 3 | 4 5 1 | 7 2 9 |
 | 7 9 5 | 3 6 2 | 1 4 8 |
   - - -   - - -   - - -  
#+END_SRC

* Calculate the table totals

Go ahead... commit the treachery of using vim as a spreadsheet.
** Start file

#+BEGIN_SRC 
+--------------+--------+----------+---------+
| Item         | Cost   | Amount   | Total   |
+==============+========+==========+=========+
| Apple        | 2.00   | 3        |         |
+--------------+--------+----------+---------+
| Orange       | 2.50   | 4        |         |
+--------------+--------+----------+---------+
| Banana       | 1.00   | 6        |         |
+--------------+--------+----------+---------+
| Kiwi         | 7.00   | 5        |         |
+--------------+--------+----------+---------+
| Mango        | 5.00   | 2        |         |
+--------------+--------+----------+---------+
| Plum         | 4.00   | 9        |         |
+--------------+--------+----------+---------+
| Nectarine    | 3.50   | 7        |         |
+--------------+--------+----------+---------+
| Watermelon   | 5.00   | 3        |         |
+--------------+--------+----------+---------+
| Grapes       | 4.00   | 2        |         |
+--------------+--------+----------+---------+
| Tangerine    | 5.00   | 6        |         |
+--------------+--------+----------+---------+
#+END_SRC

** End file

#+BEGIN_SRC 
+--------------+--------+----------+---------+
| Item         | Cost   | Amount   | Total   |
+==============+========+==========+=========+
| Apple        | 2.00   | 3        |    6.00 |
+--------------+--------+----------+---------+
| Orange       | 2.50   | 4        |   10.00 |
+--------------+--------+----------+---------+
| Banana       | 1.00   | 6        |    6.00 |
+--------------+--------+----------+---------+
| Kiwi         | 7.00   | 5        |   35.00 |
+--------------+--------+----------+---------+
| Mango        | 5.00   | 2        |   10.00 |
+--------------+--------+----------+---------+
| Plum         | 4.00   | 9        |   36.00 |
+--------------+--------+----------+---------+
| Nectarine    | 3.50   | 7        |   24.50 |
+--------------+--------+----------+---------+
| Watermelon   | 5.00   | 3        |   15.00 |
+--------------+--------+----------+---------+
| Grapes       | 4.00   | 2        |    8.00 |
+--------------+--------+----------+---------+
| Tangerine    | 5.00   | 6        |   30.00 |
+--------------+--------+----------+---------+
#+END_SRC

* Double and switch

Aaaanother case switcher
** Start file
#+BEGIN_SRC 
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
#+END_SRC

** End file
#+BEGIN_SRC 
Aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAAAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAAAAAAAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAAAAAAAAAAAAAAAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aaaaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aaaaaaaaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aaaaaaaaaaaaaaaaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
Aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
#+END_SRC

* Ninjas Leaderboard

The two lines in "Start file" has an obfuscated email address. Second line give an index (from 1 to 30) to the chars list of the first line, for example, the first char of email (n) is in position 25, second char (i) is in position 19 and s.o.
** Start file
#+BEGIN_SRC 
['l', 'b', '@', 'o', 's', 'd', 'd', '.', 'L', 'a', 'm', 'o', 'f', 'c', 'm', 'g', 'r', 'v', 'r', 'i', 'o', 'e', 'a', 'j', 'e', 'n', 'i', 'n', '_', 'a']
[25, 19, 27, 23, 9, 4, 28, 8, 21, 22, 6, 24, 18, 1, 11, 29, 16, 5, 2, 17, 26, 10, 15, 20, 0, 12, 7, 13, 3, 14]
#+END_SRC

** End file
#+BEGIN_SRC 
['l', 'b', '@', 'o', 's', 'd', 'd', '.', 'L', 'a', 'm', 'o', 'f', 'c', 'm', 'g', 'r', 'v', 'r', 'i', 'o', 'e', 'a', 'j', 'e', 'n', 'i', 'n', '_', 'a']
[25, 19, 27, 23, 9, 4, 28, 8, 21, 22, 6, 24, 18, 1, 11, 29, 16, 5, 2, 17, 26, 10, 15, 20, 0, 12, 7, 13, 3, 14]
ninjas_Leaderboard@vimgolf.com
#+END_SRC

* Printable ASCII characters

From a blank input, print all 95 printing ASCII characters one per line, from space to tilde.
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
 
!
"
#
$
%
&
'
(
)
*
+
,
-
.
/
0
1
2
3
4
5
6
7
8
9
:
;
<
=
>
?
@
A
B
C
D
E
F
G
H
I
J
K
L
M
N
O
P
Q
R
S
T
U
V
W
X
Y
Z
[
\
]
^
_
`
a
b
c
d
e
f
g
h
i
j
k
l
m
n
o
p
q
r
s
t
u
v
w
x
y
z
{
|
}
~
#+END_SRC

* Letters are numbers

Letters and numbers are interchangeable. A lot of programming languages give you simple ways to convert individual letters to hex, binary and decimal but does Vim?
** Start file
#+BEGIN_SRC 
Letters can also be numbers. Not sure how it works but it does
#+END_SRC

** End file
#+BEGIN_SRC 
761011161161011141153299971103297108115111329810132110117109981011141154632781111163211511711410132104111119321051163211911111410711532981171163210511632100111101115
#+END_SRC

* Land of the Lost

Enter the tabs below the lyrics
** Start file
#+BEGIN_SRC 
Marshall, Will and Holly on a routine expedition
Met the greatest earthquake ever known
#+END_SRC

** End file
#+BEGIN_SRC 
Marshall, Will and Holly on a routine expedition
   #t   #r   #s   #r   #a   #v   #n
Met the greatest earthquake ever known
    #h    #a    #e    #u    #v    #o
#+END_SRC

* Comparing scores

If Alice and Bob both did the challenge, put their entries together in the top paragraph, so we can compare their scores more easily.
** Start file
#+BEGIN_SRC 
4d1a34ccfa85f32065000004 Alice: 15 # Simple text editing with Vim
4d1a8bf2b8cb3409320002c4 Alice: 12 # Search and Replace 0
4d1cdb0635b40650b8000527 Alice: 16 # Make Fancy Header
4d716c76919202611400002b Alice: 19 # Numbering a List
4f0720c8f037090001000007 Alice: 11 # switch variable
4fca29ddd3a0d40001000038 Alice: 8  # Remove semicolons after expressions
50048db8cdc4060002000004 Alice: 22 # Vertical Limit
508fe9f57acca60002000037 Alice: 13 # Stairs Indenting
5192f96ad8df110002000002 Alice: 16 # Words in parens

4d1a34ccfa85f32065000004 Bob: 13 # Simple text editing with Vim
4d1a8bf2b8cb3409320002c4 Bob: 14 # Search and Replace 0
4d1aaf2fb11838287d000036 Bob: 14 # Reverse characters in a line
4d2c9d06eda6262e4e00007a Bob: 19 # Assignment Alignment
4ef209ef78702b0001000019 Bob: 14 # Make it more readable
4f0720c8f037090001000007 Bob: 11 # switch variable
4fc9d767d3a0d4000100000e Bob: 12 # Append semicolon after expressions
50048db8cdc4060002000004 Bob: 23 # Vertical Limit
508fe9f57acca60002000037 Bob: 14 # Stairs Indenting
5192f96ad8df110002000002 Bob: 15 # Words in parens
#+END_SRC

** End file
#+BEGIN_SRC 
4d1a34ccfa85f32065000004 Alice: 15 # Simple text editing with Vim
4d1a34ccfa85f32065000004 Bob: 13 # Simple text editing with Vim
4d1a8bf2b8cb3409320002c4 Alice: 12 # Search and Replace 0
4d1a8bf2b8cb3409320002c4 Bob: 14 # Search and Replace 0
4f0720c8f037090001000007 Alice: 11 # switch variable
4f0720c8f037090001000007 Bob: 11 # switch variable
50048db8cdc4060002000004 Alice: 22 # Vertical Limit
50048db8cdc4060002000004 Bob: 23 # Vertical Limit
508fe9f57acca60002000037 Alice: 13 # Stairs Indenting
508fe9f57acca60002000037 Bob: 14 # Stairs Indenting
5192f96ad8df110002000002 Alice: 16 # Words in parens
5192f96ad8df110002000002 Bob: 15 # Words in parens

4d1cdb0635b40650b8000527 Alice: 16 # Make Fancy Header
4d716c76919202611400002b Alice: 19 # Numbering a List
4fca29ddd3a0d40001000038 Alice: 8  # Remove semicolons after expressions

4d1aaf2fb11838287d000036 Bob: 14 # Reverse characters in a line
4d2c9d06eda6262e4e00007a Bob: 19 # Assignment Alignment
4ef209ef78702b0001000019 Bob: 14 # Make it more readable
4fc9d767d3a0d4000100000e Bob: 12 # Append semicolon after expressions
#+END_SRC

* Word Blender

The insides of long words seem to have been run through the blender. Can you fix this famous tale, brave knight?
** Start file
#+BEGIN_SRC 
             A CUCITCENNOT YEKNAE IN KNIG
                    AUHTRR'S CRUOT

IT was in Wciwrak Cltsae taht I cmae asorcs the
cuoirus segnartr wohm I am gniog to tlak auobt.
He aetcarttd me by terhe tgnihs: his cidnad sticilpmiy,
his muolevras ftirailimay wtih aneicnt aomrr, and the
rsenluftses of his cnapmoy -- for he did all the tniklag.
We flel tehtegor, as msedot plpoee wlil, in the tial of
the hred taht was bnieg swohn tguorhh, and he at ocne
bagen to say tgnihs wcihh ietseretnd me. As he
teklad anolg, sltfoy, pltnasaely, flgniwoly, he semeed
to dfirt aawy ilbitpecrepmy out of tihs wlrod and tmie,
and itno smoe rtomee era and old fettogron crtnuoy;
and so he gllaudary wvoe scuh a slepl auobt me taht I
semeed to mvoe anomg the sretceps and swodahs and
dsut and mlod of a gary atiuqitny, hnidlog sceeph wtih
a rilec of it! Eltcaxy as I wluod saepk of my nseraet
panosrel fdneirs or eeimens, or my msot failimar
nrobhgies, he skope of Sir Brevidee, Sir Bros de
Ginas, Sir Lolecnuat of the Lkae, Sir Gahalad, and all
the oehtr gaert nemas of the Tlbae Rnuod -- and how
old, old, ulbakaepsny old and fedad and dry and
mtsuy and aneicnt he cmae to look as he wnet on!
Pltnesery he tenrud to me and siad, jsut as one mhgit
saepk of the wehtaer, or any oehtr common mettar.
#+END_SRC

** End file
#+BEGIN_SRC 
             A CONNECTICUT YANKEE IN KING
                    ARTHUR'S COURT

IT was in Warwick Castle that I came across the
curious stranger whom I am going to talk about.
He attracted me by three things: his candid simplicity,
his marvelous familiarity with ancient armor, and the
restfulness of his company -- for he did all the talking.
We fell together, as modest people will, in the tail of
the herd that was being shown through, and he at once
began to say things which interested me. As he
talked along, softly, pleasantly, flowingly, he seemed
to drift away imperceptibly out of this world and time,
and into some remote era and old forgotten country;
and so he gradually wove such a spell about me that I
seemed to move among the specters and shadows and
dust and mold of a gray antiquity, holding speech with
a relic of it! Exactly as I would speak of my nearest
personal friends or enemies, or my most familiar
neighbors, he spoke of Sir Bedivere, Sir Bors de
Ganis, Sir Launcelot of the Lake, Sir Galahad, and all
the other great names of the Table Round -- and how
old, old, unspeakably old and faded and dry and
musty and ancient he came to look as he went on!
Presently he turned to me and said, just as one might
speak of the weather, or any other common matter.
#+END_SRC

* Format the output

Sometimes your standard out is a little hard to read. Take this multilevel hash and make it human readable.
** Start file
#+BEGIN_SRC 
{Vertex('x'): {Vertex('v'): Edge(Vertex('v'), Vertex('x')), Vertex('z'): Edge(Vertex('z'), Vertex('x')), Vertex('y'): Edge(Vertex('y'), Vertex('x'))}, Vertex('y'): {Vertex('x'): Edge(Vertex('y'), Vertex('x')), Vertex('w'): Edge(Vertex('w'), Vertex('y')), Vertex('z'): Edge(Vertex('z'), Vertex('y'))}, Vertex('z'): {Vertex('x'): Edge(Vertex('z'), Vertex('x')), Vertex('y'): Edge(Vertex('z'), Vertex('y')), Vertex('u'): Edge(Vertex('u'), Vertex('z'))}, Vertex('u'): {Vertex('v'): Edge(Vertex('v'), Vertex('u')), Vertex('w'): Edge(Vertex('w'), Vertex('u')), Vertex('z'): Edge(Vertex('u'), Vertex('z'))}, Vertex('v'): {Vertex('u'): Edge(Vertex('v'), Vertex('u')), Vertex('x'): Edge(Vertex('v'), Vertex('x')), Vertex('w'): Edge(Vertex('w'), Vertex('v'))}, Vertex('w'): {Vertex('u'): Edge(Vertex('w'), Vertex('u')), Vertex('v'): Edge(Vertex('w'), Vertex('v')), Vertex('y'): Edge(Vertex('w'), Vertex('y'))}}
#+END_SRC

** End file
#+BEGIN_SRC 
{
  Vertex('x'): {
    Vertex('v'): Edge(Vertex('v'), Vertex('x')), 
    Vertex('z'): Edge(Vertex('z'), Vertex('x')), 
    Vertex('y'): Edge(Vertex('y'), Vertex('x'))
  },
  Vertex('y'): {
    Vertex('x'): Edge(Vertex('y'), Vertex('x')), 
    Vertex('w'): Edge(Vertex('w'), Vertex('y')), 
    Vertex('z'): Edge(Vertex('z'), Vertex('y'))
  },
  Vertex('z'): {
    Vertex('x'): Edge(Vertex('z'), Vertex('x')), 
    Vertex('y'): Edge(Vertex('z'), Vertex('y')), 
    Vertex('u'): Edge(Vertex('u'), Vertex('z'))
  },
  Vertex('u'): {
    Vertex('v'): Edge(Vertex('v'), Vertex('u')), 
    Vertex('w'): Edge(Vertex('w'), Vertex('u')), 
    Vertex('z'): Edge(Vertex('u'), Vertex('z'))
  },
  Vertex('v'): {
    Vertex('u'): Edge(Vertex('v'), Vertex('u')), 
    Vertex('x'): Edge(Vertex('v'), Vertex('x')), 
    Vertex('w'): Edge(Vertex('w'), Vertex('v'))
  },
  Vertex('w'): {
    Vertex('u'): Edge(Vertex('w'), Vertex('u')), 
    Vertex('v'): Edge(Vertex('w'), Vertex('v')), 
    Vertex('y'): Edge(Vertex('w'), Vertex('y'))
  }
}
#+END_SRC

* Replace Parameter with Explicit Methods

Implementing the methods of a Java Interface
** Start file
#+BEGIN_SRC 
import ch.xyz.Logger;

public class LoggerImpl implements Logger {

        private void log(LogLevel lvl, String str) {
                /* Code */
        }

        @Override
        public void emerge(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void alert(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void critical(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void warning(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void notice(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void info(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

        @Override
        public void debug(String str) {
                throw new UnsupportedOperationException("Not supported yet.");
        }

}
#+END_SRC

** End file
#+BEGIN_SRC 
import ch.xyz.Logger;

public class LoggerImpl implements Logger {

        private void log(LogLevel lvl, String str) {
                /* Code */
        }

        @Override
        public void emerge(String str) {
                log(LogLevel.EMERGE, str);
        }

        @Override
        public void alert(String str) {
                log(LogLevel.ALERT, str);
        }

        @Override
        public void critical(String str) {
                log(LogLevel.CRITICAL, str);
        }

        @Override
        public void warning(String str) {
                log(LogLevel.WARNING, str);
        }

        @Override
        public void notice(String str) {
                log(LogLevel.NOTICE, str);
        }

        @Override
        public void info(String str) {
                log(LogLevel.INFO, str);
        }

        @Override
        public void debug(String str) {
                log(LogLevel.DEBUG, str);
        }

}
#+END_SRC

* Square numbers

Boring math puzzle.
** Start file
#+BEGIN_SRC 
0
#+END_SRC

** End file
#+BEGIN_SRC 
0
1
4
9
16
25
36
49
64
81
100
#+END_SRC

* Converting group lines from format A to Format B

Convert from one format to another
** Start file
#+BEGIN_SRC 
ABCDEFGHIJKL        00100     C                    N12345678W1234567891234       GND   99999MMY LITTLE TEST                000000000
ABCDEFGHIJKL        00100     H N12345678W123456789                              GND   99999MANOTHER LITTLE TEST           000000000
ABCDEFGHIJKL        00200     L N12345678W123456789N12345678W12345678912341234                                             000000000
ABCDEFGHIJKL        00300     G N12345678W123456789
#+END_SRC

** End file
#+BEGIN_SRC 
0010|C|||N12345678|W123456789|123.4
0010|H|N12345678|W123456789||
0020|L|N12345678|W123456789|N12345678|W123456789|123.4|123.4
0030|G|N12345678|W123456789||
#+END_SRC

* Flatten repo

For each git repository (<project> tag) translate name attribute to flatten directory structure. Add path attribute if missing (because checkout hierarchy must be kept). #xml
** Start file
#+BEGIN_SRC 
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote fetch="/home/matt/test-01" name="mirror" review="vimgolf.org"/>
  <default remote="mymirror" revision="myandroid-1.2.3"/>
  <project name="device/common"/>
  <project name="device/generic/common" revision="11c092a6cbfcf6207f07a9a8e3398e747e7f5461"/>
  <project groups="pdk" name="device/generic/arm64"/>
  <project groups="pdk" name="platform/abi/cpp" path="abi/cpp"/>
  <project name="platform/bootable/recovery" path="bootable/recovery"/>
  <project name="platform/build" path="build">
    <copyfile dest="Makefile" src="core/root.mk"/>
  </project>
  <project name="platform/external/bzip2" path="external/bzip2"/>
  <project name="kernel/matt-3.18" path="kernel" upstream="myandroid-1.2.4"/>
</manifest>
#+END_SRC

** End file
#+BEGIN_SRC 
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <remote fetch="/home/matt/test-01" name="mirror" review="vimgolf.org"/>
  <default remote="mymirror" revision="myandroid-1.2.3"/>
  <project path="device/common" name="device_common"/>
  <project path="device/generic/common" name="device_generic_common" revision="11c092a6cbfcf6207f07a9a8e3398e747e7f5461"/>
  <project groups="pdk" path="device/generic/arm64" name="device_generic_arm64"/>
  <project groups="pdk" name="platform_abi_cpp" path="abi/cpp"/>
  <project name="platform_bootable_recovery" path="bootable/recovery"/>
  <project name="platform_build" path="build">
    <copyfile dest="Makefile" src="core/root.mk"/>
  </project>
  <project name="platform_external_bzip2" path="external/bzip2"/>
  <project name="kernel_matt-3.18" path="kernel" upstream="myandroid-1.2.4"/>
</manifest>
#+END_SRC

* paste indent correction - JS

You copy some javascript code from a website and paste it into vim, it does not look good!
** Start file
#+BEGIN_SRC 
function AlbumCtrl($scope, $http) {
      $scope.url = 'http://onehungrymind.com/angular-album/images.json';
          $scope.images = [];
              $scope.imageCategories = [];
                  $scope.currentImage = {};

                      function handleImagesLoaded(data, status) {
                                $scope.images = data;
                                        $scope.currentImage = _.first($scope.images);
                                                $scope.imageCategories = _.uniq(_.pluck($scope.images, 'category'));
                                                    }

                          $scope.fetch = function () {
                                    $http.get($scope.url).success($scope.handleImagesLoaded);
                                        }

                              $scope.setCurrentImage = function (image) {
                                        $scope.currentImage = image;
                                            };

                                  $scope.fetch();
}
#+END_SRC

** End file
#+BEGIN_SRC 
function AlbumCtrl($scope, $http) {
    $scope.url = 'http://onehungrymind.com/angular-album/images.json';
    $scope.images = [];
    $scope.imageCategories = [];
    $scope.currentImage = {};

    function handleImagesLoaded(data, status) {
        $scope.images = data;
        $scope.currentImage = _.first($scope.images);
        $scope.imageCategories = _.uniq(_.pluck($scope.images, 'category'));
    }

    $scope.fetch = function () {
        $http.get($scope.url).success($scope.handleImagesLoaded);
    }

    $scope.setCurrentImage = function (image) {
        $scope.currentImage = image;
    };

    $scope.fetch();
}
#+END_SRC

* Linear congruential generator

http://en.wikipedia.org/wiki/Linear_congruential_generator
** Start file
#+BEGIN_SRC 
a = 25
b = 7
m = 48
x0 = 0
x1 = (a * x0 + b) % m
x2 = (a * x1 + b) % m
...

|
v
#+END_SRC

** End file
#+BEGIN_SRC 
a = 25
b = 7
m = 48
x0 = 0
x1 = (a * x0 + b) % m
x2 = (a * x1 + b) % m
...

|
v

0
7
38
45
28
35
18
25
8
15
46
5
36
43
26
33
16
23
6
13
44
3
34
41
24
31
14
21
4
11
42
1
32
39
22
29
12
19
2
9
40
47
30
37
20
27
10
17
0
#+END_SRC

* Roman numerals

Use the substitutions on top to convert unary to Roman numerals.
** Start file
#+BEGIN_SRC 
IIIII,V
IIII,IV
VV,X
VIV,IX
XXXXX,L
XXXX,XL

III
IIII
IIIII
IIIIIII
IIIIIIIII
IIIIIIIIII
IIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII
IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIIII
 vim: set gdefault:
#+END_SRC

** End file
#+BEGIN_SRC 
IIIII,V
IIII,IV
VV,X
VIV,IX
XXXXX,L
XXXX,XL

III
IV
V
VII
IX
X
XVIII
XXI
XXXIX
XL
XLIV
L
LXIV
 vim: set gdefault:
#+END_SRC

* It's a factor

Flaunt your macro prowess by factoring some numbers. Too hard? It takes less than 30 strokes, I promise.
** Start file
#+BEGIN_SRC 
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
#+END_SRC

** End file
#+BEGIN_SRC 
1
1 2
1 3
1 2 4
1 5
1 2 3 6
1 7
1 2 4 8
1 3 9
1 2 5 10
1 11
1 2 3 4 6 12
1 13
1 2 7 14
1 3 5 15
1 2 4 8 16
1 17
1 2 3 6 9 18
1 19
1 2 4 5 10 20
#+END_SRC

* Remove Accent off the Letter

Remove all the accent from extremely accented statements.
** Start file
#+BEGIN_SRC 
1.001.01a a̱gnim ī̍ḻe pu̱rohi̍taṁ ya̱jñasya̍ de̱vam ṛ̱tvija̍m ।
1.001.01c hotā̍raṁ ratna̱dhāta̍mam ॥
#+END_SRC

** End file
#+BEGIN_SRC 
1.001.01a agnim ile purohitam yajnasya devam rtvijam ।
1.001.01c hotaram ratnadhatamam ॥
#+END_SRC

* HTML formatting: vertical alignment for readability

We did this a VimGolf challenge at work and now that we have finished I want to see if you guys can come up with something even better than we could. Our best solution was 44 keystrokes.
** Start file
#+BEGIN_SRC 
<table>
<thead>
<th>
<th id="first_name">First Name</th>
<th id="last_name">Last Name</th>
<th id="address">Address</th>
<th id="city">City</th>
<th id="state">State</th>
<th id="zip_postal">Zip</th>
<th id="country">Country</th>
<th id="phone">Phone</th>
</th>
</thead>
</table>
#+END_SRC

** End file
#+BEGIN_SRC 
<table>
        <thead>
                <th>
                <th id="first_name"> First Name</th>
                <th id="last_name "> Last Name </th>
                <th id="address   "> Address   </th>
                <th id="city      "> City      </th>
                <th id="state     "> State     </th>
                <th id="zip_postal"> Zip       </th>
                <th id="country   "> Country   </th>
                <th id="phone     "> Phone     </th>
                </th>
        </thead>
</table>
#+END_SRC

* Sierpinski's Triangle

Build the famous fractal, Sierpinski's Triangle.
** Start file
#+BEGIN_SRC 
 ^
/_\ 
#+END_SRC

** End file
#+BEGIN_SRC 
                               ^
                              /_\
                             ^   ^
                            /_\ /_\
                           ^       ^
                          /_\     /_\
                         ^   ^   ^   ^
                        /_\ /_\ /_\ /_\
                       ^               ^
                      /_\             /_\
                     ^   ^           ^   ^
                    /_\ /_\         /_\ /_\
                   ^       ^       ^       ^
                  /_\     /_\     /_\     /_\
                 ^   ^   ^   ^   ^   ^   ^   ^
                /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\
               ^                               ^
              /_\                             /_\
             ^   ^                           ^   ^
            /_\ /_\                         /_\ /_\
           ^       ^                       ^       ^
          /_\     /_\                     /_\     /_\
         ^   ^   ^   ^                   ^   ^   ^   ^
        /_\ /_\ /_\ /_\                 /_\ /_\ /_\ /_\
       ^               ^               ^               ^
      /_\             /_\             /_\             /_\
     ^   ^           ^   ^           ^   ^           ^   ^
    /_\ /_\         /_\ /_\         /_\ /_\         /_\ /_\
   ^       ^       ^       ^       ^       ^       ^       ^
  /_\     /_\     /_\     /_\     /_\     /_\     /_\     /_\
 ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^   ^
/_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\ /_\
#+END_SRC

* Execute immediate SQL

Sql string tranformation ...
** Start file
#+BEGIN_SRC 
insert into tabtmp
(no_part,
deptname,
firtname,
lastname
)
select
no_part,
deptname,
firtname,
lastname
from
emp e,dept d
where e.no_part=10
and d.no_part=10
and e.deptno=d.deptno;
#+END_SRC

** End file
#+BEGIN_SRC 
c_part:=10;
execute immediate
" insert into tabtmp"||
" (no_part,"||
" deptname,"||
" firtname,"||
" lastname"||
" )"||
" select"||
" no_part,"||
" deptname,"||
" firtname,"||
" lastname"||
" from"||
" emp e,dept d"||
" where e.no_part="||c_part||
" and d.no_part="||c_part||
" and e.deptno=d.deptno";
#+END_SRC

* Lower cased and dashed strings

As I have to generate big fixtures files, I wanted to find a way to format input data the way described by start and end files. Especially the lower-cased-and-dashed ids Not so good to find a pure Vim way, that's why I submit this challenge ;)
** Start file
#+BEGIN_SRC 
Lôrem Ipsum
Dolor.eros
Auctor: eros (elémentum)
Tincïdunt, âc
#+END_SRC

** End file
#+BEGIN_SRC 
lorem-ipsum:
    name: "Lôrem Ipsum"
dolor-eros:
    name: "Dolor.eros"
auctor-eros-elementum:
    name: "Auctor: eros (elémentum)"
tincidunt-ac:
    name: "Tincïdunt, âc"
#+END_SRC

* Create an alphabet diamond

Here's a brain teaser to keep things interesting...
** Start file
#+BEGIN_SRC 
A
#+END_SRC

** End file
#+BEGIN_SRC 
                         AA
                        BBBB
                       CCCCCC
                      DDDDDDDD
                     EEEEEEEEEE
                    FFFFFFFFFFFF
                   GGGGGGGGGGGGGG
                  HHHHHHHHHHHHHHHH
                 IIIIIIIIIIIIIIIIII
                JJJJJJJJJJJJJJJJJJJJ
               KKKKKKKKKKKKKKKKKKKKKK
              LLLLLLLLLLLLLLLLLLLLLLLL
             MMMMMMMMMMMMMMMMMMMMMMMMMM
            NNNNNNNNNNNNNNNNNNNNNNNNNNNN
           OOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
          PPPPPPPPPPPPPPPPPPPPPPPPPPPPPPPP
         QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ
        RRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRR
       SSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSS
      TTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTT
     UUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUU
    VVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVV
   WWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWW
  XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
 YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY
ZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ
ZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ
 YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY
  XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
   WWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWWW
    VVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVVV
     UUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUU
      TTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTTT
       SSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSSS
        RRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRRR
         QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ
          PPPPPPPPPPPPPPPPPPPPPPPPPPPPPPPP
           OOOOOOOOOOOOOOOOOOOOOOOOOOOOOO
            NNNNNNNNNNNNNNNNNNNNNNNNNNNN
             MMMMMMMMMMMMMMMMMMMMMMMMMM
              LLLLLLLLLLLLLLLLLLLLLLLL
               KKKKKKKKKKKKKKKKKKKKKK
                JJJJJJJJJJJJJJJJJJJJ
                 IIIIIIIIIIIIIIIIII
                  HHHHHHHHHHHHHHHH
                   GGGGGGGGGGGGGG
                    FFFFFFFFFFFF
                     EEEEEEEEEE
                      DDDDDDDD
                       CCCCCC
                        BBBB
                         AA
#+END_SRC

* Before there was Farmville...

There was old MacDonald. For my toddler. The first Vim sing-a-long?
** Start file
#+BEGIN_SRC 
cows moo
horses neigh
ducks quack
geese honk
hens cluck
chicks peep
pigs oink
sheep baa
#+END_SRC

** End file
#+BEGIN_SRC 
Old MacDonald had a farm, E I E I O.
And on that farm he had a cow, E I E I O.
With a moo, moo here and a moo, moo there.
Here a moo, there a moo, everywhere a moo, moo.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a horse, E I E I O.
With a neigh, neigh here and a neigh, neigh there.
Here a neigh, there a neigh, everywhere a neigh, neigh.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a duck, E I E I O.
With a quack, quack here and a quack, quack there.
Here a quack, there a quack, everywhere a quack, quack.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a goose, E I E I O.
With a honk, honk here and a honk, honk there.
Here a honk, there a honk, everywhere a honk, honk.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a hen, E I E I O.
With a cluck, cluck here and a cluck, cluck there.
Here a cluck, there a cluck, everywhere a cluck, cluck.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a chick, E I E I O.
With a peep, peep here and a peep, peep there.
Here a peep, there a peep, everywhere a peep, peep.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a pig, E I E I O.
With an oink, oink here and an oink, oink there.
Here an oink, there an oink, everywhere an oink, oink.
Old MacDonald had a farm, E I E I O.

Old MacDonald had a farm, E I E I O.
And on that farm he had a sheep, E I E I O.
With a baa, baa here and a baa, baa there.
Here a baa, there a baa, everywhere a baa, baa.
Old MacDonald had a farm, E I E I O.
#+END_SRC

* Chucking wood

An exercise in compressing repetitive text. For this challenge, any entry that uses keys outside the main row (such as arrow keys, Home, End, Delete, etc.) will be removed. (Esc is OK, though you should be using C-[ anyway.)
** Start file
#+BEGIN_SRC 
#+END_SRC

** End file
#+BEGIN_SRC 
How much wood could a woodchuck chuck if a woodchuck could chuck wood?
#+END_SRC

* PHP <--> Java class conversion Part 2

Same class but reverse!
** Start file
#+BEGIN_SRC 
public class Foo
{
        private double var1;
        private double var2;

        public Foo(double val)
        {
                init(val);
                doSomething();
        }

        private void init(double val)
        {
                var1 = val;
        }
        
        private void doSomething()
        {
                var2 = Math.sqrt(var1);
        }

        public double getResult()
        {
                return var2;
        }
}
#+END_SRC

** End file
#+BEGIN_SRC 
<?php
class Foo
{
        private $var1;
        private $var2;

        public function Foo($val)
        {
                $this->init($val);
                $this->doSomething();
        }

        private function init($val)
        {
                $this->var1 = $val;
        }
        
        private function doSomething()
        {
                $this->var2 = sqrt($this->var1);
        }

        public function getResult()
        {
                return $this->var2;
        }
}
?>
#+END_SRC

* Complete the circuit grid!

Continuing from the last challenge, add additional rows to the grid. Change each of the names from 'A1'...'A10' to 'B1'...'B10', 'C1'...'C10', etc, and for each new row add 0.7 to the X values in the (X Y) at the end of each line.
** Start file
#+BEGIN_SRC 
smd .5 .5 -100 'A1' (0 -1.2)
smd .5 .5 -100 'A2' (0 -0.5)
smd .5 .5 -100 'A3' (0 0.2)
smd .5 .5 -100 'A4' (0 0.9)
smd .5 .5 -100 'A5' (0 1.6)
smd .5 .5 -100 'A6' (0 2.3)
smd .5 .5 -100 'A7' (0 3.0)
smd .5 .5 -100 'A8' (0 3.7)
smd .5 .5 -100 'A9' (0 4.4)
smd .5 .5 -100 'A10' (0 5.1)
#+END_SRC

** End file
#+BEGIN_SRC 
smd .5 .5 -100 'A1' (0 -1.2)
smd .5 .5 -100 'A2' (0 -0.5)
smd .5 .5 -100 'A3' (0 0.2)
smd .5 .5 -100 'A4' (0 0.9)
smd .5 .5 -100 'A5' (0 1.6)
smd .5 .5 -100 'A6' (0 2.3)
smd .5 .5 -100 'A7' (0 3.0)
smd .5 .5 -100 'A8' (0 3.7)
smd .5 .5 -100 'A9' (0 4.4)
smd .5 .5 -100 'A10' (0 5.1)

smd .5 .5 -100 'B1' (0.7 -1.2)
smd .5 .5 -100 'B2' (0.7 -0.5)
smd .5 .5 -100 'B3' (0.7 0.2)
smd .5 .5 -100 'B4' (0.7 0.9)
smd .5 .5 -100 'B5' (0.7 1.6)
smd .5 .5 -100 'B6' (0.7 2.3)
smd .5 .5 -100 'B7' (0.7 3.0)
smd .5 .5 -100 'B8' (0.7 3.7)
smd .5 .5 -100 'B9' (0.7 4.4)
smd .5 .5 -100 'B10' (0.7 5.1)

smd .5 .5 -100 'C1' (1.4 -1.2)
smd .5 .5 -100 'C2' (1.4 -0.5)
smd .5 .5 -100 'C3' (1.4 0.2)
smd .5 .5 -100 'C4' (1.4 0.9)
smd .5 .5 -100 'C5' (1.4 1.6)
smd .5 .5 -100 'C6' (1.4 2.3)
smd .5 .5 -100 'C7' (1.4 3.0)
smd .5 .5 -100 'C8' (1.4 3.7)
smd .5 .5 -100 'C9' (1.4 4.4)
smd .5 .5 -100 'C10' (1.4 5.1)

smd .5 .5 -100 'D1' (2.1 -1.2)
smd .5 .5 -100 'D2' (2.1 -0.5)
smd .5 .5 -100 'D3' (2.1 0.2)
smd .5 .5 -100 'D4' (2.1 0.9)
smd .5 .5 -100 'D5' (2.1 1.6)
smd .5 .5 -100 'D6' (2.1 2.3)
smd .5 .5 -100 'D7' (2.1 3.0)
smd .5 .5 -100 'D8' (2.1 3.7)
smd .5 .5 -100 'D9' (2.1 4.4)
smd .5 .5 -100 'D10' (2.1 5.1)
#+END_SRC

* Not enough Ps

Different type of code
** Start file
#+BEGIN_SRC 
A B C D
B A X Y
B X Y D
D C B A
X D A B
B W Y D
W B D X
A B D X
D Z B Y
D Z B A
#+END_SRC

** End file
#+BEGIN_SRC 
A P C D
P A X Y
B X Y D
D C P A
X D A P
B W Y D
W B D X
A P D X
D Z B Y
D Z P A
#+END_SRC

* SFD-ROC: ROT13 Phonics

A is for apple, b is for ball, etc... This familiar phonics poem has been rotated 13 characters. Make the letter match the word.
** Start file
#+BEGIN_SRC 
n is for alsamixer
o is for bash
p is for cat
q is for dmesg
r is for echo
s is for find
t is for grep
u is for htop
v is for ifconfig
w is for jobs
x is for killall
y is for less
z is for mkdir
a is for nethack
b is for octocat
c is for ping
d is for quiz
e is for rm
f is for scp
g is for time
h is for unzip
i is for vim
j is for wget
k is for xteddy
l is for yes
m is for zip
#+END_SRC

** End file
#+BEGIN_SRC 
a is for alsamixer
b is for bash
c is for cat
d is for dmesg
e is for echo
f is for find
g is for grep
h is for htop
i is for ifconfig
j is for jobs
k is for killall
l is for less
m is for mkdir
n is for nethack
o is for octocat
p is for ping
q is for quiz
r is for rm
s is for scp
t is for time
u is for unzip
v is for vim
w is for wget
x is for xteddy
y is for yes
z is for zip
#+END_SRC

* Make the circuit grid!

Copy this command for a circuit layout program to create 10 total smd commands. Increment the number in quotes to name each pad, and add 0.7 to each of the (X Y) coordinates at the end of each line.
** Start file
#+BEGIN_SRC 
smd .5 .5 -100 'A1' (0 -1.2)
#+END_SRC

** End file
#+BEGIN_SRC 
smd .5 .5 -100 'A1' (0 -1.2)
smd .5 .5 -100 'A2' (0 -0.5)
smd .5 .5 -100 'A3' (0 0.2)
smd .5 .5 -100 'A4' (0 0.9)
smd .5 .5 -100 'A5' (0 1.6)
smd .5 .5 -100 'A6' (0 2.3)
smd .5 .5 -100 'A7' (0 3.0)
smd .5 .5 -100 'A8' (0 3.7)
smd .5 .5 -100 'A9' (0 4.4)
smd .5 .5 -100 'A10' (0 5.1)
#+END_SRC

* SQL to YAML

Should be easy with vim, or not?
** Start file
#+BEGIN_SRC 
(1,'cleora.baugh@example.com','2016-02-12 09:00:09',NULL),
(2,'hedy.van-gossard@example.com','2016-02-12 09:00:09',NULL),
(2,'bryce.steeves@example.com','2016-02-12 09:00:09',NULL),
(3,'rodger.van-harland@example.com','2016-02-12 09:00:09',NULL),
(3,'jami.waid@example.com','2016-02-12 09:00:09',NULL),
#+END_SRC

** End file
#+BEGIN_SRC 
cleora.baugh:
    group_id: 1
    full_name: Cleora Baugh
    mail: cleora.baugh@example.com
hedy.van-gossard:
    group_id: 2
    full_name: Hedy van Gossard
    mail: hedy.van-gossard@example.com
bryce.steeves:
    group_id: 2
    full_name: Bryce Steeves
    mail: bryce.steeves@example.com
rodger.van-harland:
    group_id: 3
    full_name: Rodger van Harland
    mail: rodger.van-harland@example.com
jami.waid:
    group_id: 3
    full_name: Jami Waid
    mail: jami.waid@example.com
#+END_SRC

* Transposition

Transpose the original lines in separate columns, one for each line.
** Start file
#+BEGIN_SRC 
ultricies, vehicula, felis, sed, auctor, aenean, euismod, semper, quam, dapibus
nibh, consequat, consequat, maecenas, sit, amet, mauris, justo, quis, porttitor
curabitur, pharetra, euismod, orci, sit, amet, ullamcorper, mi, tincidunt, et
vitae, lorem, at, mi, feugiat, convallis, ac, eget, dui, fusce
blandit, iaculis, nulla, sit, amet, dolor, nec, est, ornare, volutpat
#+END_SRC

** End file
#+BEGIN_SRC 
ultricies  nibh       curabitur    vitae      blandit
vehicula   consequat  pharetra     lorem      iaculis
felis      consequat  euismod      at         nulla
sed        maecenas   orci         mi         sit
auctor     sit        sit          feugiat    amet
aenean     amet       amet         convallis  dolor
euismod    mauris     ullamcorper  ac         nec
semper     justo      mi           eget       est
quam       quis       tincidunt    dui        ornare
dapibus    porttitor  et           fusce      volutpat
#+END_SRC

* Lookahead and Lookbehind

Look everywhere
** Start file
#+BEGIN_SRC 
Example for reference:

:%s/\(some\)\@<=thing/one/g
searches for all strings starting with some, then matching thing
changes thing into one
end result: something becomes someone

:%s/\(some\)\@<!thing/one/g
searches for all strings not starting with some, then matching thing
changes thing into one
end result: something is not changed, but everything changes to everyone

:%s/some\(thing\)\@=/every/g
searches for all strings ending with thing, then matching some
changes some into every
end result: something becomes everything

:%s/some\(thing\)\@!/every/g
searches for all strings not ending with thing, then matching some
changes some into every
end result: something is not changed, but someone becomes everyone
#+END_SRC

** End file
#+BEGIN_SRC 
Example for reference:

:%s/\(some\)\@<=thing/one/g
searches for all strings starting with some, then matching thing
changes thing into one
end result: someone becomes someone

:%s/\(some\)\@<!thing/one/g
searches for all strings not starting with some, then matching thing
changes thing into one
end result: something is not changed, but everyone changes to everyone

:%s/some\(thing\)\@=/every/g
searches for all strings ending with thing, then matching some
changes some into every
end result: everything becomes everything

:%s/some\(thing\)\@!/every/g
searches for all strings not ending with thing, then matching some
changes some into every
end result: something is not changed, but everyone becomes everyone
#+END_SRC

* Python: Lots of function arguments

The function definition is too long for one line. The modeline helps you with some typical Python indent settings.
** Start file
#+BEGIN_SRC 
class Pointless:
    def lotsa_arguments(self, first, second, third, fourth, fifth, sixth, seventh, eighth, ninth, tenth, eleventh, twelfth, thirteenth, fourteenth, sixteenth, seventeenth, eighteenth, nineteenth, twentieth, twenty_first, twenty_second, twenty_third):
        "Doesn't even use all those arguments. What a waste."
        pass


# File-specific indent settings!
# More VimGolf challenges need modelines.
# vim: set sw=4 et ft=python:
#+END_SRC

** End file
#+BEGIN_SRC 
class Pointless:
    def lotsa_arguments(self, first, second, third, fourth, fifth, sixth,
                        seventh, eighth, ninth, tenth, eleventh, twelfth,
                        thirteenth, fourteenth, sixteenth, seventeenth,
                        eighteenth, nineteenth, twentieth, twenty_first,
                        twenty_second, twenty_third):
        "Doesn't even use all those arguments. What a waste."
        pass


# File-specific indent settings!
# More VimGolf challenges need modelines.
# vim: set sw=4 et ft=python:
#+END_SRC

* Flip the chessboard

White's turn is over. Flip the board to black's perspective. I added coordinates to frustrate you.
** Start file
#+BEGIN_SRC 
  a b c d e f g h
8 r n b q k b n r
7 p p p p p p p p
6 . . . . . . . .
5 . . . . . . . .
4 . . . . P . . .
3 . . . . . . . .
2 P P P P . P P P
1 R N B Q K B N R
#+END_SRC

** End file
#+BEGIN_SRC 
  h g f e d c b a
1 R N B K Q B N R
2 P P P . P P P P
3 . . . . . . . .
4 . . . P . . . .
5 . . . . . . . .
6 . . . . . . . .
7 p p p p p p p p
8 r n b k q b n r
#+END_SRC

* Permutations N=4

Could use backtracking or other algorithm to generate sorted numbers. Second chance !
** Start file
#+BEGIN_SRC 
1234
#+END_SRC

** End file
#+BEGIN_SRC 
1234
1243
1324
1342
1423
1432
2134
2143
2314
2341
2413
2431
3124
3142
3214
3241
3412
3421
4123
4132
4213
4231
4312
4321
#+END_SRC

* Harder than "abcd > a b c d"

Not as easy as the last challenge. This time, just one space between a and b, up to 25 spaces between y and z. (Removed some lines; diff was too long.)
** Start file
#+BEGIN_SRC 
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
a b c d e f g h i j k l m n o p q r s t u v w x y z
#+END_SRC

** End file
#+BEGIN_SRC 
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z
a b  c   d    e     f      g       h        i         j          k           l            m             n              o               p                q                 r                  s                   t                    u                     v                      w                       x                        y                         z

#+END_SRC

* SFD-ROC: ASCII Logo Border

Draw a border around this familiar logo ;)
** Start file
#+BEGIN_SRC 
                                      :M
                                     MMMMM
       MMMMMMMMMMMMMMMMMMMMMMMMMMMMDM++M$NM.    MMMMMMMMMMMMMMMMMMMMMMMMMMM
     :MMM777777777777777777777777MMMZ+MOM$$MM MMMN88888888888888888888888DMMM
     MMD.~~~~~~~~~~~~~~~~~~~~~~~~.8MMOOOOO$$$MMM..~~~~~~~~~~~~~~~~~~~~~~~:ZMM
     MMD.~~~~~~~~~~~~~~~~~~~~~~~~78MMOOOOOOM$$MM.N~~~~~~~~~~~~~~~~~~~~~~~~IMM
     MMD.~~~~~~~~~~~~~~~~~~~~~~~~78MMOOOOOOOO$MM.N~~~~~~~~~~~~~~~~~~~~~~~OIMM
     MMM.$III8~~~~~~~~~~~~~~OIII7IMMMOOOOOOOOOMMN.IIII~~~~~~~~~~~~~~~~~~II$MM
      NMMMMM.8~~~~~~~~~~~~~~IIDMMMMMOOOOOOOOOOOMMMMMM.~~~~~~~~~~~~~~~~NIIMMM
        ~~MM.8~~~~~~~~~~~~~~IIDMMMDOOOOOOOOOOOOOMMM..,~~~~~~~~~~~~~~~IIDMMN
          MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOOOOMMM8..=~~~~~~~~~~~~~~DIIMMM
          MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOOOMMM..?~~~~~~~~~~~~~~~IIMMMI
          MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOMMM8..?~~~~~~~~~~~~~~DIIMMM
          MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOMMM..~~~~~~~~~~~~~~~~IIMMMZ
          MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOMMM:..~~~~~~~~~~~~~~~NIIMMM
          MM.8~~~~~~~~~~~~~~IIDMMOOOOO8MMM..8~~~~~~~~~~~~~~~IIMMM:
          MM.8~~~~~~~~~~~~~~IIDMMOOOOMMM...~~~~~~~~~~~~~~~8I7MMMM.
          MM.8~~~~~~~~~~~~~~IIDMMOOMMMO..8~~~~~~~~~~~~~~=IIMMMM$$MM
          MM.8~~~~~~~~~~~~~~IIDMMOMMM...~~~~~~~~~~~~~~~$IOMMMOOO$$$M7
         MMM.8~~~~~~~~~~~~~~IIDMMMMO..D~~~~~~~~~~~~~~~IIMMMOOOOOOM$$MM
       MM+MM.8~~~~~~~~~~~~~~IIDMMM...~~~~~~~~~~~~~~~8I$MMMOOOOOOOOO$$ZM7
     :MZ++MM.8~~~~~~~~~~~~~~IIDM,..$~~~~~~~~~~~~~~=IIMMMOOOOOOOOOOOOM$$MM
    MM++MOMM.8~~~~~~~~~~~~~~IID..:~~~~~~~~~~~~~~~$IDMMMOOOOOOOOOOOOOOO8$$MM
  8M+++OOOMM.8~~~~~~~~~~~~~~II..=~~~~~~~~~~~~~~?IIMMMOOOOOOOOOOOOOOOOOOD$$NM.
 MM++MOOOOMM.8~~~~~~~~~~~~~~I.$~~~~~~~~~~~~~~~7IMMMDOOOOOOOOOOOOOOOOOOOOOM$$MM
 MM888OOOOMM.8~~~~~~~~~~~~~~?+~~~~~~~~~~~~~7MMMMMMOOOOOOOOOOOOOOOOOOOOOOMDDNM:
   MM88MOOMM.8~~~~~~~~~~~~~~~~~~~~~~~~~~~~MM~~~~MMOOOOOOOOOOOOOOOOOOOOONDDMM
    +MD88DMM.8~~~~~~~~~~~~~~~~~~~~~~~~~~~IM~~~~~M8OOOOOOOOOOOOOOOOOOOMDDMM
      MM88MM.8~~~~~~~~~~~~~~~~~~~~~~~~~~7MD~~~~MMOOOOOOOOOOOOOOOOOO8DDNM8
        MMMM.8~~~~~~~~~~~~~~~~~~~~~~~~ZI7MMMMMMMOOOOOOOOOOOOOOOOOOMDDMM
         MMM.8~~~~~~~~~~~~~~~~~~~~~~~77MMM888888O8888888OOOO8888MDDNM=~~~~~
          MM.8~~~~~~~~~~~~~~~~~~~~~+IMMMMMMMMMM8MMMMMMMMMOOMMMMMMMMMMMMMMMMM
          MM.8~~~~~~~~~~~~~~~~~~~~7IMM??=~~~~MM8MII~~~~~8MM+~~~~~~MMM~~~~~~DM
          MM.8~~~~~~~~~~~~~~~~~~$I$MMMMM~~~~~MO88M+~~~~~~~~~~~~~~~~~~~~~~~~MD
          MM.8~~~~~~~~~~~~~~~~~7IMMMOOM+~~~~MMOOMM~~~~MMMMMM~~~~DMMMMM~~~~?M
          MM.8~~~~~~~~~~~~~~~DIDMMMOOMM~~~~~MOOOM~~~~~MO8DM+~~~~M~  MO~~~~MD
          MM.8~~~~~~~~~~~~~~IIMMMOOOOM~~~~~MMOOMM~~~~MMMDMM~~~~MM  7M~~~~+M
          MM.8~~~~~~~~~~~~NIMMMDOOOOMM~~~~IMOOOM~~~~~MDDNM+~~~~M:  MO~~~~MM
          MM.8~~~~~~~~~~~7IMMMOOOOOOM~~~~~MMOOMM~~~~MMDMMM~~~~NM  =M~~~~~M
          MM.8~~~~~~~~~DIMMMNOOOOOOMM~~~~$MOOOM~~~~~MNM,MI~~~~M:  MD~~~~MM
          MM.8~~~~~~~~IIMMM88MOOOO8M~~~~~88MNMM~~~~ZNM DM~~~~88M:+M~~~~~ZMM
          MM.8~~~~~~NIMMM,+MD88DOOMMMMMMMMMM8MMMMMMMM+ MMMMMMMMM MMMMMMMMM
          MM:.DDDDDI7MMM    MM88DOOOOOOOOOOOO8DDNM8
          .MMMMMMMMMMM.      .MM88MOOOOOOOOOMDDMM
            8MMMMMMMM          MM88DOOOOOO8DDNM8
                                 MM88MOOOMDDMM
                                  MM888MDDNM,
                                    MM8MDMM
                                     +MMM
                                       8
                                                                 GlassGiant.com
#+END_SRC

** End file
#+BEGIN_SRC 
--------------------------------------------------------------------------------
|                                     :M                                       |
|                                    MMMMM                                     |
|      MMMMMMMMMMMMMMMMMMMMMMMMMMMMDM++M$NM.    MMMMMMMMMMMMMMMMMMMMMMMMMMM    |
|    :MMM777777777777777777777777MMMZ+MOM$$MM MMMN88888888888888888888888DMMM  |
|    MMD.~~~~~~~~~~~~~~~~~~~~~~~~.8MMOOOOO$$$MMM..~~~~~~~~~~~~~~~~~~~~~~~:ZMM  |
|    MMD.~~~~~~~~~~~~~~~~~~~~~~~~78MMOOOOOOM$$MM.N~~~~~~~~~~~~~~~~~~~~~~~~IMM  |
|    MMD.~~~~~~~~~~~~~~~~~~~~~~~~78MMOOOOOOOO$MM.N~~~~~~~~~~~~~~~~~~~~~~~OIMM  |
|    MMM.$III8~~~~~~~~~~~~~~OIII7IMMMOOOOOOOOOMMN.IIII~~~~~~~~~~~~~~~~~~II$MM  |
|     NMMMMM.8~~~~~~~~~~~~~~IIDMMMMMOOOOOOOOOOOMMMMMM.~~~~~~~~~~~~~~~~NIIMMM   |
|       ~~MM.8~~~~~~~~~~~~~~IIDMMMDOOOOOOOOOOOOOMMM..,~~~~~~~~~~~~~~~IIDMMN    |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOOOOMMM8..=~~~~~~~~~~~~~~DIIMMM      |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOOOMMM..?~~~~~~~~~~~~~~~IIMMMI       |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOOMMM8..?~~~~~~~~~~~~~~DIIMMM         |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOOOMMM..~~~~~~~~~~~~~~~~IIMMMZ          |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOOOOMMM:..~~~~~~~~~~~~~~~NIIMMM            |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOO8MMM..8~~~~~~~~~~~~~~~IIMMM:             |
|         MM.8~~~~~~~~~~~~~~IIDMMOOOOMMM...~~~~~~~~~~~~~~~8I7MMMM.             |
|         MM.8~~~~~~~~~~~~~~IIDMMOOMMMO..8~~~~~~~~~~~~~~=IIMMMM$$MM            |
|         MM.8~~~~~~~~~~~~~~IIDMMOMMM...~~~~~~~~~~~~~~~$IOMMMOOO$$$M7          |
|        MMM.8~~~~~~~~~~~~~~IIDMMMMO..D~~~~~~~~~~~~~~~IIMMMOOOOOOM$$MM         |
|      MM+MM.8~~~~~~~~~~~~~~IIDMMM...~~~~~~~~~~~~~~~8I$MMMOOOOOOOOO$$ZM7       |
|    :MZ++MM.8~~~~~~~~~~~~~~IIDM,..$~~~~~~~~~~~~~~=IIMMMOOOOOOOOOOOOM$$MM      |
|   MM++MOMM.8~~~~~~~~~~~~~~IID..:~~~~~~~~~~~~~~~$IDMMMOOOOOOOOOOOOOOO8$$MM    |
| 8M+++OOOMM.8~~~~~~~~~~~~~~II..=~~~~~~~~~~~~~~?IIMMMOOOOOOOOOOOOOOOOOOD$$NM.  |
|MM++MOOOOMM.8~~~~~~~~~~~~~~I.$~~~~~~~~~~~~~~~7IMMMDOOOOOOOOOOOOOOOOOOOOOM$$MM |
|MM888OOOOMM.8~~~~~~~~~~~~~~?+~~~~~~~~~~~~~7MMMMMMOOOOOOOOOOOOOOOOOOOOOOMDDNM: |
|  MM88MOOMM.8~~~~~~~~~~~~~~~~~~~~~~~~~~~~MM~~~~MMOOOOOOOOOOOOOOOOOOOOONDDMM   |
|   +MD88DMM.8~~~~~~~~~~~~~~~~~~~~~~~~~~~IM~~~~~M8OOOOOOOOOOOOOOOOOOOMDDMM     |
|     MM88MM.8~~~~~~~~~~~~~~~~~~~~~~~~~~7MD~~~~MMOOOOOOOOOOOOOOOOOO8DDNM8      |
|       MMMM.8~~~~~~~~~~~~~~~~~~~~~~~~ZI7MMMMMMMOOOOOOOOOOOOOOOOOOMDDMM        |
|        MMM.8~~~~~~~~~~~~~~~~~~~~~~~77MMM888888O8888888OOOO8888MDDNM=~~~~~    |
|         MM.8~~~~~~~~~~~~~~~~~~~~~+IMMMMMMMMMM8MMMMMMMMMOOMMMMMMMMMMMMMMMMM   |
|         MM.8~~~~~~~~~~~~~~~~~~~~7IMM??=~~~~MM8MII~~~~~8MM+~~~~~~MMM~~~~~~DM  |
|         MM.8~~~~~~~~~~~~~~~~~~$I$MMMMM~~~~~MO88M+~~~~~~~~~~~~~~~~~~~~~~~~MD  |
|         MM.8~~~~~~~~~~~~~~~~~7IMMMOOM+~~~~MMOOMM~~~~MMMMMM~~~~DMMMMM~~~~?M   |
|         MM.8~~~~~~~~~~~~~~~DIDMMMOOMM~~~~~MOOOM~~~~~MO8DM+~~~~M~  MO~~~~MD   |
|         MM.8~~~~~~~~~~~~~~IIMMMOOOOM~~~~~MMOOMM~~~~MMMDMM~~~~MM  7M~~~~+M    |
|         MM.8~~~~~~~~~~~~NIMMMDOOOOMM~~~~IMOOOM~~~~~MDDNM+~~~~M:  MO~~~~MM    |
|         MM.8~~~~~~~~~~~7IMMMOOOOOOM~~~~~MMOOMM~~~~MMDMMM~~~~NM  =M~~~~~M     |
|         MM.8~~~~~~~~~DIMMMNOOOOOOMM~~~~$MOOOM~~~~~MNM,MI~~~~M:  MD~~~~MM     |
|         MM.8~~~~~~~~IIMMM88MOOOO8M~~~~~88MNMM~~~~ZNM DM~~~~88M:+M~~~~~ZMM    |
|         MM.8~~~~~~NIMMM,+MD88DOOMMMMMMMMMM8MMMMMMMM+ MMMMMMMMM MMMMMMMMM     |
|         MM:.DDDDDI7MMM    MM88DOOOOOOOOOOOO8DDNM8                            |
|         .MMMMMMMMMMM.      .MM88MOOOOOOOOOMDDMM                              |
|           8MMMMMMMM          MM88DOOOOOO8DDNM8                               |
|                                MM88MOOOMDDMM                                 |
|                                 MM888MDDNM,                                  |
|                                   MM8MDMM                                    |
|                                    +MMM                                      |
|                                      8                                       |
|                                                                GlassGiant.com|
--------------------------------------------------------------------------------
#+END_SRC

* ascii-art diamond

Simple ascii-art diamond. The grid is 40x40.
** Start file
#+BEGIN_SRC 
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
----------------------------------------
#+END_SRC

** End file
#+BEGIN_SRC 
                   /\                   
                  // \                  
                 ///  \                 
                ////   \                
               /////    \               
              //////     \              
             ///////      \             
            ////////       \            
           /////////        \           
          //////////         \          
         ///////////          \         
        ////////////           \        
       /////////////            \       
      //////////////             \      
     ///////////////              \     
    ////////////////               \    
   /////////////////                \   
  //////////////////                 \  
 ///////////////////                  \ 
////////////////////                   \
\                   ////////////////////
 \                  /////////////////// 
  \                 //////////////////  
   \                /////////////////   
    \               ////////////////    
     \              ///////////////     
      \             //////////////      
       \            /////////////       
        \           ////////////        
         \          ///////////         
          \         //////////          
           \        /////////           
            \       ////////            
             \      ///////             
              \     //////              
               \    /////               
                \   ////                
                 \  ///                 
                  \ //                  
                   \/                   
#+END_SRC

* Hanging Indent for Footnotes

Format this footnote (in kramdown syntax) so that it has hanging indent.
** Start file
#+BEGIN_SRC 
[^1]: Term regarding a generally obsolete type of website back when websites
focused less on interactive features and more just on text.

[^5]: Eroge company. Feel free to Google if you want, but beware of NSFW.

[^8]: Kuroneko says that he confessed his love, but never really specifies who
he confessed his love about (an ambiguity that is much more pronounced in
Japanese than in English). A more literal interpretation of her statement might
be “He made a statement of love to me.”

[^10]: This was literally “homoge.” I could have translated it to yaoi or BL,
but this way of saying it carries a slightly more negative connotation.
#+END_SRC

** End file
#+BEGIN_SRC 
[^1]: Term regarding a generally obsolete type of website back when websites
      focused less on interactive features and more just on text.

[^5]: Eroge company. Feel free to Google if you want, but beware of NSFW.

[^8]: Kuroneko says that he confessed his love, but never really specifies who
      he confessed his love about (an ambiguity that is much more pronounced in
      Japanese than in English). A more literal interpretation of her statement
      might be “He made a statement of love to me.”

[^10]: This was literally “homoge.” I could have translated it to yaoi or BL,
       but this way of saying it carries a slightly more negative connotation.
#+END_SRC

* Dumb to smart

Turn dumb quote to smart vim's way.
** Start file
#+BEGIN_SRC 
Dhṛtarāṣṭra said: "O Sañjaya what did my sons desirous of battle and Pāṇḍu's son do after assembling at the holy land of righteousness Kurukṣetra ?"
- 'Bhagavad Gītā's first shokla'
#+END_SRC

** End file
#+BEGIN_SRC 
Dhṛtarāṣṭra said: “O Sañjaya what did my sons desirous of battle and Pāṇḍu’s son do after assembling at the holy land of righteousness Kurukṣetra ?”
- ‘Bhagavad Gītā’s first shokla’
#+END_SRC

* Create bison tokens

Create tokens for bison out of a known list of words
** Start file
#+BEGIN_SRC 
call real integer write read while end do if then else program var begin return include
#+END_SRC

** End file
#+BEGIN_SRC 
call {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Call;
}
real {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Real;
}
integer {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Integer;
}
write {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Write;
}
read {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Read;
}
while {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return While;
}
end {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return End;
}
do {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Do;
}
if {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return If;
}
then {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Then;
}
else {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Else;
}
program {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Program;
}
var {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Var;
}
begin {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Begin;
}
return {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Return;
}
include {
        yylval.type = strdup("res");
        yylval.value = strdup(yytext);
        return Include;
}
#+END_SRC

* Tiny column alignment

Align using the four blocks, don't forget to lowercase and have fun!
** Start file
#+BEGIN_SRC 
matthieu

ILITARY
RT
HEATRE
HRILLER
ISTORICAL
NTERNATIONAL
ROTICA
TOPIA

  3 items
 39 items
351 items
 34 items
 37 items
322 items
  3 items
 30 items

::::::::
#+END_SRC

** End file
#+BEGIN_SRC 
Military      : 3 items
Art           : 39 items
Theatre       : 351 items
Thriller      : 34 items
Historical    : 37 items
International : 322 items
Erotica       : 3 items
Utopia        : 30 items
#+END_SRC

* sort python functions and methods alphabetically

* sort functions in the python file alphabetically * sort functions within a Class alphabetically * sort Classes alphabetically
** Start file
#+BEGIN_SRC 
@decorator1
def bbbb(*args):
    pass

    # do nothing here
    return


def aaa(name=xxx, arg=yux):
    pass

    # do nothing here
    return


@decorator1
@decorator2
def cccc(xpto, llxs):
    pass


class MyAAABigClass(object):
    """ MyBigClass """

    @decorator1
    @decorator2
    def cccc(xpto, llxs):
        pass

    def aaa(name=xxx, arg=yux):
        pass

        # do nothing here
        return

    @decorator1
    def bbbb(*args):
        pass

        # do nothing here
        return


class MyBBBBigClass(object):
    """ MyBigClass """

    @decorator1
    @decorator2
    def cccc(xpto, llxs):
        pass

    def aaa(name=xxx, arg=yux):
        pass

        # do nothing here
        return

    @decorator1
    def bbbb(*args):
        pass

        # do nothing here
        return
#+END_SRC

** End file
#+BEGIN_SRC 
def aaa(name=xxx, arg=yux):
    pass

    # do nothing here
    return


@decorator1
def bbbb(*args):
    pass

    # do nothing here
    return


@decorator1
@decorator2
def cccc(xpto, llxs):
    pass


class MyAAABigClass(object):
    """ MyBigClass """

    def aaa(name=xxx, arg=yux):
        pass

        # do nothing here
        return

    @decorator1
    def bbbb(*args):
        pass

        # do nothing here
        return

    @decorator1
    @decorator2
    def cccc(xpto, llxs):
        pass


class MyBBBBigClass(object):
    """ MyBigClass """

    def aaa(name=xxx, arg=yux):
        pass

        # do nothing here
        return

    @decorator1
    def bbbb(*args):
        pass

        # do nothing here
        return

    @decorator1
    @decorator2
    def cccc(xpto, llxs):
        pass
#+END_SRC

* Greek column realign

Oops one letter is missing! Shift down the second column to insert nu letter. Symbol can be entered using: <C-K>n*
** Start file
#+BEGIN_SRC 
# vim: set fenc=utf-8 expandtab virtualedit=block virtualedit?:
# This could help: %s/\s\+$//

Α       α       alpha     |    Ξ        ξ       xi
Β       β       beta      |    Ο        ο       omicron
Γ       γ       gamma     |    Π        π       pi
Δ       δ       delta     |    Ρ        ρ       rho
Ε       ε       epsilon   |    Σ        σ/ς     sigma
Ζ       ζ       zeta      |    Τ        τ       tau
Η       η       eta       |    Υ        υ       upsilon
Θ       θ       theta     |    Φ        φ       phi
Ι       ι       iota      |    Χ        χ       chi
Κ       κ       kappa     |    Ψ        ψ       psi
Λ       λ       lambda    |    Ω        ω       omega
Μ       μ       mu        |
#+END_SRC

** End file
#+BEGIN_SRC 
# vim: set fenc=utf-8 expandtab virtualedit=block virtualedit?:
# This could help: %s/\s\+$//

Α       α       alpha     |    N        ν       nu
Β       β       beta      |    Ξ        ξ       xi
Γ       γ       gamma     |    Ο        ο       omicron
Δ       δ       delta     |    Π        π       pi
Ε       ε       epsilon   |    Ρ        ρ       rho
Ζ       ζ       zeta      |    Σ        σ/ς     sigma
Η       η       eta       |    Τ        τ       tau
Θ       θ       theta     |    Υ        υ       upsilon
Ι       ι       iota      |    Φ        φ       phi
Κ       κ       kappa     |    Χ        χ       chi
Λ       λ       lambda    |    Ψ        ψ       psi
Μ       μ       mu        |    Ω        ω       omega
#+END_SRC

* Remove hard line breaks

Text files with Hard breaks are not good for e-readers. We need remove all hard line breaks and have long lines.
** Start file
#+BEGIN_SRC 
[ chapter 1 ] - we are
introduced to the narrator, a
pilot, and his ideas about
grown-ups

Once when i was six years old
i saw a magnificent picture in
a book, called true stories
from nature, about the
primeval forest. It was a
picture of a boa constrictor
in the act of swallowing an
animal. Here is a copy of the
drawing.

In the book it said: "boa
constrictors swallow their
prey whole, without chewing
it. After that they are not
able to move, and they sleep
through the six months that
they need for digestion."

I pondered deeply, then, over
the adventures of the jungle.
And after some work with a
colored pencil i succeeded in
making my first drawing. My
drawing number one. It looked
like this:

I showed my masterpiece to the
grown-ups, and asked them
whether the drawing frightened
them.

But they answered: "frighten?
Why should any one be
frightened by a hat?"

My drawing was not a picture
of a hat. It was a picture of
a boa constrictor digesting an
elephant. But since the
grown-ups were not able to
understand it, i made another
drawing: i drew the inside of
the boa constrictor, so that
the grown-ups could see it
clearly. They always need to
have things explained. My
drawing number two looked like
this:

The grown-ups response, this
time, was to advise me to lay
aside my drawings of boa
constrictors, whether from the
inside or the outside, and
devote myself instead to
geography, history, arithmetic
and grammar. That is why, at
the age of six, i gave up what
might have been a magnificent
career as a painter. I had
been disheartened by the
failure of my drawing number
one and my drawing number two.
Grown-ups never understand
anything by themselves, and it
is tiresome for children to be
always and forever explaining
things to them.

So then i chose another
profession, and learned to
pilot airplanes. I have flown
a little over all parts of the
world; and it is true that
geography has been very useful
to me. At a glance i can
distinguish china from
arizona. If one gets lost in
the night, such knowledge is
valuable.

In the course of this life i
have had a great many
encounters with a great many
people who have been concerned
with matters of consequence. I
have lived a great deal among
grown-ups. I have seen them
intimately, close at hand. And
that hasnt much improved my
opinion of them.

Whenever i met one of them who
seemed to me at all
clear-sighted, i tried the
experiment of showing him my
drawing number one, which i
have always kept. I would try
to find out, so, if this was a
person of true understanding.
But, whoever it was, he, or
she, would always say:

"that is a hat."

Then i would never talk to
that person about boa
constrictors, or primeval
forests, or stars. I would
bring myself down to his
level. I would talk to him
about bridge, and golf, and
politics, and neckties. And
the grown-up would be greatly
pleased to have met such a
sensible man.
#+END_SRC

** End file
#+BEGIN_SRC 
[ chapter 1 ] - we are introduced to the narrator, a pilot, and his ideas about grown-ups
Once when i was six years old i saw a magnificent picture in a book, called true stories from nature, about the primeval forest. It was a picture of a boa constrictor in the act of swallowing an animal. Here is a copy of the drawing.
In the book it said: "boa constrictors swallow their prey whole, without chewing it. After that they are not able to move, and they sleep through the six months that they need for digestion."
I pondered deeply, then, over the adventures of the jungle.  And after some work with a colored pencil i succeeded in making my first drawing. My drawing number one. It looked like this:
I showed my masterpiece to the grown-ups, and asked them whether the drawing frightened them.
But they answered: "frighten?  Why should any one be frightened by a hat?"
My drawing was not a picture of a hat. It was a picture of a boa constrictor digesting an elephant. But since the grown-ups were not able to understand it, i made another drawing: i drew the inside of the boa constrictor, so that the grown-ups could see it clearly. They always need to have things explained. My drawing number two looked like this:
The grown-ups response, this time, was to advise me to lay aside my drawings of boa constrictors, whether from the inside or the outside, and devote myself instead to geography, history, arithmetic and grammar. That is why, at the age of six, i gave up what might have been a magnificent career as a painter. I had been disheartened by the failure of my drawing number one and my drawing number two.  Grown-ups never understand anything by themselves, and it is tiresome for children to be always and forever explaining things to them.
So then i chose another profession, and learned to pilot airplanes. I have flown a little over all parts of the world; and it is true that geography has been very useful to me. At a glance i can distinguish china from arizona. If one gets lost in the night, such knowledge is valuable.
In the course of this life i have had a great many encounters with a great many people who have been concerned with matters of consequence. I have lived a great deal among grown-ups. I have seen them intimately, close at hand. And that hasnt much improved my opinion of them.
Whenever i met one of them who seemed to me at all clear-sighted, i tried the experiment of showing him my drawing number one, which i have always kept. I would try to find out, so, if this was a person of true understanding.  But, whoever it was, he, or she, would always say:
"that is a hat."
Then i would never talk to that person about boa constrictors, or primeval forests, or stars. I would bring myself down to his level. I would talk to him about bridge, and golf, and politics, and neckties. And the grown-up would be greatly pleased to have met such a sensible man.
#+END_SRC

* Circle of Fifths with Sharps

Display a list of the Circle of Fifths with corresponding solfege syllables with sharps. Handling spaces may be tricky.
** Start file
#+BEGIN_SRC 
Do  Sol Re  La  Mi  Ti  Fi  Di  Si  Ri  Li  Fa  Do 
 = 
C G D A E B F# C# G# D# A# F C
#+END_SRC

** End file
#+BEGIN_SRC 
Do  = C
Sol = G
Re  = D
La  = A
Mi  = E
Ti  = B
Fi  = F#
Di  = C#
Si  = G#
Ri  = D#
Li  = A#
Fa  = F
Do  = C
#+END_SRC

* Add links to an existing HTML table

Add these links at that top to the respective table cell. First link, first cell, etc.
** Start file
#+BEGIN_SRC 
http://example.com/link/to/page/1
http://example.com/link/to/page/2
http://example.com/link/to/page/3
http://example.com/link/to/page/4
http://example.com/link/to/page/5
http://example.com/link/to/page/6
http://example.com/link/to/page/7
http://example.com/link/to/page/8
http://example.com/link/to/page/9
http://example.com/link/to/page/10
http://example.com/link/to/page/11
http://example.com/link/to/page/12


<tbody>
        <tr>
                <td>Oct. 23, 2012</td>
                <td>Oct. 24, 2012</td>
        </tr>
        <tr>
                <td>Nov. 13, 2012</td>
                <td>Nov. 14, 2012</td>
        </tr>
        <tr>
                <td>Dec. 18, 2012</td>
                <td>Dec. 20, 2012</td>
        </tr>
        <tr>
                <td>Jan. 15, 2013</td>
                <td>Jan. 17, 2013</td>
        </tr>
        <tr>
                <td>Feb. 19, 2013</td>
                <td>Feb. 21, 2013</td>
        </tr>
        <tr>
                <td>March 19, 2013</td>
                <td>March 21, 2013</td>
        </tr>
        <tr>
                <td>April 16, 2013</td>
                <td>April 18, 2013</td>
        </tr>
</tbody>
#+END_SRC

** End file
#+BEGIN_SRC 
<tbody>
        <tr>
                <td><a href="http://example.com/link/to/page/1">Oct. 23, 2012</a></td>
                <td><a href="http://example.com/link/to/page/2">Oct. 24, 2012</a></td>
        </tr>
        <tr>
                <td><a href="http://example.com/link/to/page/3">Nov. 13, 2012</a></td>
                <td><a href="http://example.com/link/to/page/4">Nov. 14, 2012</a></td>
        </tr>
        <tr>
                <td><a href="http://example.com/link/to/page/5">Dec. 18, 2012</a></td>
                <td><a href="http://example.com/link/to/page/6">Dec. 20, 2012</a></td>
        </tr>
        <tr>
                <td><a href="http://example.com/link/to/page/7">Jan. 15, 2013</a></td>
                <td><a href="http://example.com/link/to/page/8">Jan. 17, 2013</a></td>
        </tr>
        <tr>
                <td><a href="http://example.com/link/to/page/9">Feb. 19, 2013</a></td>
                <td><a href="http://example.com/link/to/page/10">Feb. 21, 2013</a></td>
        </tr>
        <tr>
                <td><a href="http://example.com/link/to/page/11">March 19, 2013</a></td>
                <td><a href="http://example.com/link/to/page/12">March 21, 2013</a></td>
        </tr>
</tbody>
#+END_SRC

* Here, piggy, piggy...

Youay owknay atwhay otay oday...
** Start file
#+BEGIN_SRC 
             A CONNECTICUT YANKEE IN KING
                    ARTHUR'S COURT

It was in Warwick Castle that I came across the
curious stranger whom I am going to talk about.
He attracted me by three things: his candid simplicity,
his marvelous familiarity with ancient armor, and the
restfulness of his company -- for he did all the talking.
We fell together, as modest people will, in the tail of
the herd that was being shown through, and he at once
began to say things which interested me. As he
talked along, softly, pleasantly, flowingly, he seemed
to drift away imperceptibly out of this world and time,
and into some remote era and old forgotten country;
and so he gradually wove such a spell about me that I
seemed to move among the specters and shadows and
dust and mold of a gray antiquity, holding speech with
a relic of it! Exactly as I would speak of my nearest
personal friends or enemies, or my most familiar
neighbors, he spoke of Sir Bedivere, Sir Bors de
Ganis, Sir Launcelot of the Lake, Sir Galahad, and all
the other great names of the Table Round -- and how
old, old, unspeakably old and faded and dry and
musty and ancient he came to look as he went on!
Presently he turned to me and said, just as one might
speak of the weather, or any other common matter.
#+END_SRC

** End file
#+BEGIN_SRC 
             AWAY ONNECTICUTCAY YANKEEAY INWAY INGKAY
                    ARTHURWAY'SAY OURTCAY

Itway asway inway Arwickway Astlecay atthay Iway amecay acrossway ethay
uriouscay angerstray omwhay Iway amway oinggay otay alktay aboutway.
Ehay attractedway emay ybay eethray ingsthay: ishay andidcay implicitysay,
ishay arvelousmay amiliarityfay ithway ancientway armorway, andway ethay
estfulnessray ofway ishay ompanycay -- orfay ehay idday allway ethay alkingtay.
Eway ellfay ogethertay, asway odestmay eoplepay illway, inway ethay ailtay ofway
ethay erdhay atthay asway eingbay ownshay oughthray, andway ehay atway onceway
eganbay otay aysay ingsthay ichwhay interestedway emay. Asway ehay
alkedtay alongway, oftlysay, easantlyplay, owinglyflay, ehay eemedsay
otay iftdray awayway imperceptiblyway outway ofway isthay orldway andway imetay,
andway intoway omesay emoteray eraway andway oldway orgottenfay ountrycay;
andway osay ehay aduallygray oveway uchsay away ellspay aboutway emay atthay Iway
eemedsay otay ovemay amongway ethay ectersspay andway adowsshay andway
ustday andway oldmay ofway away aygray antiquityway, oldinghay eechspay ithway
away elicray ofway itway! Exactlyway asway Iway ouldway eakspay ofway ymay earestnay
ersonalpay iendsfray orway enemiesway, orway ymay ostmay amiliarfay
eighborsnay, ehay okespay ofway Irsay Ediverebay, Irsay Orsbay eday
Anisgay, Irsay Auncelotlay ofway ethay Akelay, Irsay Alahadgay, andway allway
ethay otherway eatgray amesnay ofway ethay Abletay Oundray -- andway owhay
oldway, oldway, unspeakablyway oldway andway adedfay andway ydray andway
ustymay andway ancientway ehay amecay otay ooklay asway ehay entway onway!
Esentlypray ehay urnedtay otay emay andway aidsay, ustjay asway oneway ightmay
eakspay ofway ethay eatherway, orway anyway otherway ommoncay attermay.
#+END_SRC

* Binary and Increment

Some numbers fun: not only increasing numbers but also increasing binary.
** Start file
#+BEGIN_SRC 
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
3'b000: clk_out = clk_in0;
#+END_SRC

** End file
#+BEGIN_SRC 
3'b000: clk_out = clk_in1;
3'b001: clk_out = clk_in2;
3'b010: clk_out = clk_in3;
3'b011: clk_out = clk_in4;
3'b100: clk_out = clk_in5;
3'b101: clk_out = clk_in6;
3'b110: clk_out = clk_in7;
3'b111: clk_out = clk_in8;
#+END_SRC

* C to VimDict

Convert a C data structure to a Vimscript dictionary.
** Start file
#+BEGIN_SRC 
{ "Return", '\n', },
{ "ampersand", '&', },
{ "apostrophe", '\'', },
{ "asciicircum", '^', },
{ "asciitilde", '~', },
{ "asterisk", '*', },
{ "at", '@', },
{ "backslash", '\\', },
#+END_SRC

** End file
#+BEGIN_SRC 
{
\  "\n" : 'Return',
\  "&"  : 'ampersand',
\  "\'" : 'apostrophe',
\  "^"  : 'asciicircum',
\  "~"  : 'asciitilde',
\  "*"  : 'asterisk',
\  "@"  : 'at',
\  "\\" : 'backslash',
\}
#+END_SRC

* JSON string rotation

Right value strings are misplaced. Just rotate them! I'm too kind with you guys and didn't included "strings with \" in it"!
** Start file
#+BEGIN_SRC 
{
  "name"  :  "y64zqe0UKLO2w",
  "id": "Le mal vient à cheval et le bonheur à pied.",
  "proverb" : "fr",
  "lang":"http:\/\/foo.com\/good\/id=",
    "rating": 4.5,
  "link" : "",
    "status": {"success":true},
  "description": "Happiness and misfortune"
}
#+END_SRC

** End file
#+BEGIN_SRC 
{
  "name"  :  "Happiness and misfortune",
  "id": "y64zqe0UKLO2w",
  "proverb" : "Le mal vient à cheval et le bonheur à pied.",
  "lang":"fr",
    "rating": 4.5,
  "link" : "http:\/\/foo.com\/good\/id=",
    "status": {"success":true},
  "description": ""
}
#+END_SRC

* Recursive Cowsay

Convert 'cowsay' statement to recursive output
** Start file
#+BEGIN_SRC 
 ________________________________________ 
/ Real Vim ninjas count every keystroke! \
\ - do you?                              /
 ---------------------------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
#+END_SRC

** End file
#+BEGIN_SRC 
 __________________________________________ 
/ ________________________________________ \
|/ Real Vim ninjas count every keystroke! \|
|\ - do you?                              /|
| ---------------------------------------- |
|        \   ^__^                          |
|         \  (oo)\_______                  |
|            (__)\       )\/\              |
|                ||----w |                 |
|                ||     ||                 |
\------------------------------------------/
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
#+END_SRC

* Return the cow

This cow is too verbose. Give it a lesson.
** Start file
#+BEGIN_SRC 
 ________________________________________
/ If you learn one useless thing every   \
| day, in a single year you'll learn 365 |
| useless things.                        |
\                   -- fortune | cowsay  /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
#+END_SRC

** End file
#+BEGIN_SRC 
 ________________________________________
/ If you learn one useless thing every   \
| day, in a single year you'll learn 365 |
| useless things.                        |
\                   -- fortune | cowsay  /
 ----------------------------------------
                    ^__^   /        
            _______/(oo)  /         
        /\/(       /(__)            
           | w----||                
           ||     ||
#+END_SRC

* TAR archive pretty print

Will you use isk ?
** Start file
#+BEGIN_SRC 
7z                         0 link to /usr/bin/7za
/bin/bash                  1029624
/bin/busybox               1837008
/bin/sh                    0 link to /bin/bash
/etc/ssh/ssh_config        1691
/home/matt/bin/bash        1099016
/usr/bin/7za               1147480
/usr/bin/awk               0 link to /bin/busybox
/usr/bin/amixer            52592
/usr/games/cowsay          4421
/usr/games/cowthink        0 link to /usr/games/cowsay
/usr/lib/libzbar.so.0.2.0  234720
/usr/sbin/addgroup         0 link to /usr/sbin/adduser
/usr/sbin/adduser          34472
/usr/share/zoneinfo/CET    2102
/tmp/ssh_config            0 link to /etc/ssh/ssh_config
#+END_SRC

** End file
#+BEGIN_SRC 
7z                         1147480
/bin/bash                  1029624
/bin/busybox               1837008
/bin/sh                    1029624
/etc/ssh/ssh_config        1691
/home/matt/bin/bash        1099016
/usr/bin/7za               1147480
/usr/bin/awk               1837008
/usr/bin/amixer            52592
/usr/games/cowsay          4421
/usr/games/cowthink        4421
/usr/lib/libzbar.so.0.2.0  234720
/usr/sbin/addgroup         34472
/usr/sbin/adduser          34472
/usr/share/zoneinfo/CET    2102
/tmp/ssh_config            1691
#+END_SRC

ib.c cleanup

cleanup the file
** Start file
#+BEGIN_SRC 
/* Fibonacci Series c language */
#include<stdio.h>
 
main()
{
   int n, first = 0, second = 1, next, c;
 
   printf("Enter the number of terms\n");
   scanf("%d",&n);
 
   printf("First %d terms of Fibonacci series are :-\n",n);
 
   for ( c = 0 ; c < n ; c++ )
   {
      if ( c <= 1 )
         next = c;
      else
      {
         next = first + second;
         first = second;
         second = next;
      }
      printf("%d\n",next);
   }
 
   return 0;
}
#+END_SRC

** End file
#+BEGIN_SRC 
/* Fibonacci Series c language */
#include<stdio.h>

main()
{
    int n, first = 0, second = 1, next, c;

    printf("Enter the number of terms\n");
    scanf("%d",&n);

    printf("First %d terms of Fibonacci series are :-\n",n);

    for ( c = 0 ; c < n ; c++ )
    {
        if ( c <= 1 )
            next = c;
        else
        {
            next = first + second;
            first = second;
            second = next;
        }
        printf("%d\n",next);
    }

    return 0;
}
#+END_SRC

* Five Pillars

Arrange all words in a table with 5 columns. The minimal space between words in columns is 2 spaces. Columns do have varying width.
** Start file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, vel euismod referrentur ei, eu vix probo consulatu dissentias. Ad possit blandit similique est, quo te habemus deserunt. Volutpat molestiae persecuti vix cu, mei invidunt deserunt at. Te equidem inermis contentiones vel. In soleat principes pri, in vocent admodum cum.
#+END_SRC

** End file
#+BEGIN_SRC 
Lorem         ipsum    dolor        sit         amet
vel           euismod  referrentur  ei          eu
vix           probo    consulatu    dissentias  Ad
possit        blandit  similique    est         quo
te            habemus  deserunt     Volutpat    molestiae
persecuti     vix      cu           mei         invidunt
deserunt      at       Te           equidem     inermis
contentiones  vel      In           soleat      principes
pri           in       vocent       admodum     cum
#+END_SRC

* mp3 - Cutlist

An audio CD was accidentally ripped into one single mp3 file. A dummy cue-file now needs to be filled out with the correct values to get single mp3 files.
** Start file
#+BEGIN_SRC 
FILE "FILENAME.MP3" MP3
  TRACK 01 AUDIO
    TITLE "Song1"
    PERFORMER "Artist"
    INDEX 01 0:00
  TRACK 02 AUDIO
    TITLE "Song2"
    PERFORMER "Artist"
    INDEX 01 00:00:00
  TRACK 03 AUDIO
    TITLE "Song3"
    PERFORMER "Artist"
    INDEX 01 00:00:00


Bandname_Albumname.mp3
1) 00:00 - la la la
2) 04:14 - bla bla
3) 08:21 - cha cha
#+END_SRC

** End file
#+BEGIN_SRC 
FILE "Bandname_Albumname.mp3" MP3
  TRACK 01 AUDIO
    TITLE "La La La"
    PERFORMER "Bandname"
    INDEX 01 00:00:00
  TRACK 02 AUDIO
    TITLE "Bla Bla"
    PERFORMER "Bandname"
    INDEX 01 04:14:00
  TRACK 03 AUDIO
    TITLE "Cha Cha"
    PERFORMER "Bandname"
    INDEX 01 08:21:00
#+END_SRC

* Chinese Multiplication Table

Print a Chinese multiplication table in Vim. In China, every kid is asked to memorize this table. And thanks to the mono-syllabism of Chinese characters, it is not that hard. Printing the multiplication table is also a good exercise for programming beginners. For-loop, escaped characters, etc... There should be some special ways to print it in Vim.
** Start file
#+BEGIN_SRC 
1*1=1
#+END_SRC

** End file
#+BEGIN_SRC 
1*1=1
1*2=2 2*2=4
1*3=3 2*3=6  3*3=9
1*4=4 2*4=8  3*4=12 4*4=16
1*5=5 2*5=10 3*5=15 4*5=20 5*5=25
1*6=6 2*6=12 3*6=18 4*6=24 5*6=30 6*6=36
1*7=7 2*7=14 3*7=21 4*7=28 5*7=35 6*7=42 7*7=49
1*8=8 2*8=16 3*8=24 4*8=32 5*8=40 6*8=48 7*8=56 8*8=64
1*9=9 2*9=18 3*9=27 4*9=36 5*9=45 6*9=54 7*9=63 8*9=72 9*9=81
#+END_SRC

* Carriage return

I have some raw data from terminal output which uses carriege return for formatting. Carriage return sets the pointer to the first character on the line, and subsequent characters will overwrite what was there before. The challange is to simulate the terminal behaviour in vim. I'm kind of unsure if I should have skipped lines 9 and 15, since there might be some interesting solutions which are not that generic. Happy Golfing!
** Start file
#+BEGIN_SRC 
+--------------------------+
|                          |
| A nice header in a frame
+--------------------------+


Emacs rules!
Vim  


A short line
Some longer text replacing it

+----------------+
|                |
| Another header
+----------------+

Several carriege returns on a line
O few  
A

B few more simple ones
A
two reduce the amount
to 
off specializing the solution
of 
dust for this file
j
#+END_SRC

** End file
#+BEGIN_SRC 
+--------------------------+
| A nice header in a frame |
+--------------------------+


Vim   rules!


Some longer text replacing it

+----------------+
| Another header |
+----------------+

A few   carriege returns on a line

A few more simple ones
to  reduce the amount
of  specializing the solution
just for this file
#+END_SRC

* Enharmonic Equivalents

Transform # and b to digraphs
** Start file
#+BEGIN_SRC 
Enharmonic Equivalents
C# = Db
D# = Eb
F# = Gb
G# = Ab
A# = Bb
#+END_SRC

** End file
#+BEGIN_SRC 
Enharmonic Equivalents
C♯ = D♭
D♯ = E♭
F♯ = G♭
G♯ = A♭
A♯ = B♭
#+END_SRC

* Untangle my tail, please!

You know, this words were playing to chase their tails and Oops! What happened? Now we have a complete mess, their tails are totally tangled, can you please help them to untangle their tails?
** Start file
#+BEGIN_SRC 
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet.
#+END_SRC

** End file
#+BEGIN_SRC 
Loerz ipfhz doybe sig amrg, coafrgrghe saqvcfpvat elvge, seq dinz noahzl eiezbq
tezcbe inivqhag ut laober et doyber matan alvdhlnz erng, seq dinz voyhcghn. At
veeb eof et acphfnz et jufgb dub doyberf et ea reohz. Strg clvgn kafq guoretera,
no sen taxvzngn saapghf esg Loerz ipfhz doybe sig amrg.
#+END_SRC

* Coordinates placeholder

Place coordinates instead of target search.
** Start file
#+BEGIN_SRC 
test bla test test
test test
#+END_SRC

** End file
#+BEGIN_SRC 
1,1
10,1
15,1
1,2
6,2
#+END_SRC

* Merge blank lines and properly capitalize

Here you need complete 2 tasks: 1. Remove all unwanted continuous blank lines and leave only 1 blank line between paragraphs. 2. Properly capitalize the sentences.
** Start file
#+BEGIN_SRC 
the little prince visits the geographer



the sixth planet was ten times larger than the last one. it was inhabited by an old gentleman who wrote voluminous books.


"oh, look! here is an explorer!" he exclaimed to himself when he saw the little prince coming.


the little prince sat down on the table and panted a little. he had already traveled so much and so far!


"where do you come from?" the old gentleman said to him.


"what is that big book?" said the little prince. "what are you doing?"
#+END_SRC

** End file
#+BEGIN_SRC 
The little prince visits the geographer

The sixth planet was ten times larger than the last one. It was inhabited by an old gentleman who wrote voluminous books.

"Oh, look! Here is an explorer!" He exclaimed to himself when he saw the little prince coming.

The little prince sat down on the table and panted a little. He had already traveled so much and so far!

"Where do you come from?" The old gentleman said to him.

"What is that big book?" Said the little prince. "What are you doing?"
#+END_SRC

* Convert regular pandoc footnotes to in-line notes

Pandoc extends markdown by allowing footnotes, which are usually represented with a footnote identifier followed later in the document by the footnote itself. But Pandoc also allows inline footnotes without identifiers. How many strokes does it take to convert regular footnotes to inline notes? (NB: I've had trouble figuring out whether text-width makes a difference to Vimgolf in comparing the input and output file. I finally tested this locally using the Vimgolf vimrc and did a "gq" on the entire buffer as the last step. Apologies if I'm making a newbie mistake. First time submitter.)
** Start file
#+BEGIN_SRC 
American democracy means, at the very least, majority rule. And Wendell
Phillips was, above all, a democrat. “I plant myself always on
democratic principles," Phillips said in 1865. "I am a democrat,
ingrained, from top to toe.”[^1]

Of course, Phillips could not always be so explicit in calling himself a
democrat, because during his lifetime, the Democratic Party was
committed officially to silencing abolitionists like him. But in
retrospect, few things about Phillips are clearer than that he was a
democrat. In an era when even the Democratic Party committed itself, at
most, to universal white manhood suffrage, Phillips advocated the right
to vote without respect to sex or complexion, and he also publicly
supported the efforts of democratic reformers abroad like the British
Chartists at a time when even male suffrage was still rare and
controversial outside the United States. The abolitionist and Chartist
exile to the United States John C. Cluer, for example, vouched for
Phillips as "a genuine Democrat," and claimed to know that Phillips,
while in England in 1840, had "perilled his popularity by finding his
way into a loft among the Chartists," and speaking and sympathizing with
them, "instead of seeking introductions to the aristocracy."[^2]

A far-sighted advocate for the right to vote, Phillips also planted
himself on the broader democratic principle that the people and "public
opinion" should rule. In an important 1852 speech entitled "Public
Opinion," Phillips even declared that "the people never err." He did not
mean, of course, that every "single verdict which the people of to-day
may record" was right, as he immediately clarified. But he did believe
that "the great democratic tendencies of the masses" moved in the
direction of right, especially over the long run. If, as James Brewer
Stewart notes in his biography, Phillips was born "an offspring of
aristocrats," as a man he became a democrat of democrats.[^3]

[^1]: "Massachusetts Anti-Slavery Society Annual Meeting," *Liberator*,
    17 February 1865. Phillips made the statement while arguing for
    voting rights for freedmen in the South.

[^2]: "Twenty-Ninth Annual Meeting of the Massachusetts Anti-Slavery
    Society," *Liberator*, 31 January 1862. Phillips's longstanding
    commitments to the expansion of suffrage are sometimes overlooked
    because in the 1840s and 1850s Phillips himself, like many
    Garrisonians, refused to vote under a proslavery Constitution. Yet
    Phillips's position was much like Garrison, who explained his
    support for women's right to vote in 1850 by saying that "I want the
    women to have the right to vote, and I call upon them to demand it
    perseveringly until they possess it. When they have obtained it, it
    will be for them to say whether they will exercise it or not."
    Garrison quoted in John L. Thomas, *The Liberator: William Lloyd
    Garrison, A Biography* (Boston: Little, Brown, 1963), 372-373; see
    also Kraditor, *Means and Ends in American Abolitionism*, 59.

[^3]: Wendell Phillips, "Public Opinion," in *Speeches, Lectures and
    Letters* (Boston: James Redpath, 1863), 45-46; James Brewer Stewart,
    *Wendell Phillips: Liberty's Hero* (Baton Rouge: Louisiana State
    University Press, 1986, 3).
#+END_SRC

** End file
#+BEGIN_SRC 
American democracy means, at the very least, majority rule. And Wendell
Phillips was, above all, a democrat. “I plant myself always on democratic
principles," Phillips said in 1865. "I am a democrat, ingrained, from top to
toe.”^["Massachusetts Anti-Slavery Society Annual Meeting," *Liberator*, 17
February 1865. Phillips made the statement while arguing for voting rights for
freedmen in the South.]

Of course, Phillips could not always be so explicit in calling himself a
democrat, because during his lifetime, the Democratic Party was committed
officially to silencing abolitionists like him. But in retrospect, few things
about Phillips are clearer than that he was a democrat. In an era when even the
Democratic Party committed itself, at most, to universal white manhood
suffrage, Phillips advocated the right to vote without respect to sex or
complexion, and he also publicly supported the efforts of democratic reformers
abroad like the British Chartists at a time when even male suffrage was still
rare and controversial outside the United States. The abolitionist and Chartist
exile to the United States John C. Cluer, for example, vouched for Phillips as
"a genuine Democrat," and claimed to know that Phillips, while in England in
1840, had "perilled his popularity by finding his way into a loft among the
Chartists," and speaking and sympathizing with them, "instead of seeking
introductions to the aristocracy."^["Twenty-Ninth Annual Meeting of the
Massachusetts Anti-Slavery Society," *Liberator*, 31 January 1862. Phillips's
longstanding commitments to the expansion of suffrage are sometimes overlooked
because in the 1840s and 1850s Phillips himself, like many Garrisonians,
refused to vote under a proslavery Constitution. Yet Phillips's position was
much like Garrison, who explained his support for women's right to vote in 1850
by saying that "I want the women to have the right to vote, and I call upon
them to demand it perseveringly until they possess it. When they have obtained
it, it will be for them to say whether they will exercise it or not." Garrison
quoted in John L. Thomas, *The Liberator: William Lloyd Garrison, A Biography*
(Boston: Little, Brown, 1963), 372-373; see also Kraditor, *Means and Ends in
American Abolitionism*, 59.]

A far-sighted advocate for the right to vote, Phillips also planted himself on
the broader democratic principle that the people and "public opinion" should
rule. In an important 1852 speech entitled "Public Opinion," Phillips even
declared that "the people never err." He did not mean, of course, that every
"single verdict which the people of to-day may record" was right, as he
immediately clarified. But he did believe that "the great democratic tendencies
of the masses" moved in the direction of right, especially over the long run.
If, as James Brewer Stewart notes in his biography, Phillips was born "an
offspring of aristocrats," as a man he became a democrat of democrats.^[Wendell
Phillips, "Public Opinion," in *Speeches, Lectures and Letters* (Boston: James
Redpath, 1863), 45-46; James Brewer Stewart, *Wendell Phillips: Liberty's Hero*
(Baton Rouge: Louisiana State University Press, 1986, 3).]
#+END_SRC

* un-C-escape string

Convert escape sequences to characters
** Start file
#+BEGIN_SRC 
s\x6fme\tt\x65xt\n\"Sa\155ba\u201d: \\\\net\\share
\x73\x75\x70\x65\x72\x63\x61\x6c\x69\x66\x72\x61\x67\x69\x6c\x69\x73\x74\x69\x63\x65\x78\x70\x69\x61\x6c\x69\x64\x6f\x63\x69\x6f\x75\x73
#+END_SRC

** End file
#+BEGIN_SRC 
some    text
"Samba”: \\net\share
supercalifragilisticexpialidocious
#+END_SRC

* Across-Down Flip

Do this instead of the Sunday crossword.
** Start file
#+BEGIN_SRC 
pump mocha some
anis agios kbar
disintegrations
roc ice snidest
inarch readd   
  tee ser boite
spam mutational
eel copycat fed
clodhopper oils
tegua res urd  
   bleed enserf
seabeds ama leu
antihistaminics
goon cooly etui
alps tress byrl
#+END_SRC

** End file
#+BEGIN_SRC 
padri sect saga
union pele enol
miscatalog atop
psi rem dubbins
  nice chaleh  
match moo edict
ogee suppressor
cig retyped toe
horseraces aals
asana tar emmys
  tidbit unai  
skiddoo ors neb
oboe infidelity
mans tael recur
erst elds fusil
#+END_SRC

* Extended Customer 2

Format the chars
** Start file
#+BEGIN_SRC 
----------------------------------------------------
|   Custship    |     Cust      |  Extended Price  |
----------------------------------------------------
| Karen         | AA            |       1 400,00 $ |
----------------------------------------------------
| Karen         | AA            |         105,00 $ |
----------------------------------------------------
| Christina     | D             |         300,00 $ |
----------------------------------------------------
| Christina     | D             |         530,00 $ |
----------------------------------------------------
| Christina     | D             |          35,00 $ |
----------------------------------------------------
| John          | L             |         270,00 $ |
----------------------------------------------------
| John          | L             |         920,00 $ |
----------------------------------------------------
| Elizabeth     | H             |         276,00 $ |
----------------------------------------------------
| Christina     | D             |         184,00 $ |
----------------------------------------------------
| Soo           | CC            |         127,50 $ |
----------------------------------------------------
| Thomas        | C             |       1 930,00 $ |
----------------------------------------------------
| Francisco     | F             |         680,00 $ |
----------------------------------------------------
| Amritansh     | BB            |      13 800,00 $ |
----------------------------------------------------
| Elizabeth     | H             |       1 275,00 $ |
----------------------------------------------------
| Roland        | J             |         598,00 $ |
----------------------------------------------------
| Ming-Yang     | G             |      13 800,00 $ |
----------------------------------------------------
| Roland        | J             |         250,00 $ |
----------------------------------------------------
| Roland        | J             |         220,00 $ |
----------------------------------------------------
| Roland        | J             |          92,00 $ |
----------------------------------------------------
| Peter         | K             |          70,00 $ |
----------------------------------------------------
| Peter         | K             |         149,50 $ |
----------------------------------------------------
| Anna          | A             |         450,00 $ |
----------------------------------------------------
| Anna          | A             |       1 150,00 $ |
----------------------------------------------------
| Anna          | A             |          74,75 $ |
----------------------------------------------------
| Amritansh     | BB            |         482,50 $ |
----------------------------------------------------
| Amritansh     | BB            |         920,00 $ |
----------------------------------------------------
| Sven          | I             |       1 950,00 $ |
----------------------------------------------------
| Sven          | I             |       1 740,00 $ |
----------------------------------------------------
| Francisco     | F             |       4 200,00 $ |
----------------------------------------------------
| Elizabeth     | H             |       1 000,00 $ |
----------------------------------------------------
| Elizabeth     | H             |         230,00 $ |
----------------------------------------------------
| John          | Y             |         200,00 $ |
----------------------------------------------------
| Run           | Z             |         533,75 $ |
----------------------------------------------------
| Run           | Z             |         289,50 $ |
----------------------------------------------------
| Run           | Z             |         552,00 $ |
----------------------------------------------------
| Soo           | CC            |       1 218,00 $ |
----------------------------------------------------
| Francisco     | F             |         127,50 $ |
----------------------------------------------------
| Karen         | AA            |                  |
----------------------------------------------------
| Christina     | D             |       3 240,00 $ |
----------------------------------------------------
| Christina     | D             |         280,00 $ |
----------------------------------------------------
| John          | L             |                  |
----------------------------------------------------
| Elizabeth     | H             |       1 392,00 $ |
----------------------------------------------------
| Christina     | D             |                  |
----------------------------------------------------
| Soo           | CC            |                  |
----------------------------------------------------
| Thomas        | C             |         500,00 $ |
----------------------------------------------------
| Thomas        | C             |         120,00 $ |
----------------------------------------------------
| Francisco     | F             |                  |
----------------------------------------------------
| Amritansh     | BB            |                  |
----------------------------------------------------
| Elizabeth     | H             |                  |
----------------------------------------------------
| Roland        | J             |         200,00 $ |
----------------------------------------------------
| Ming-Yang     | G             |                  |
----------------------------------------------------
| Roland        | J             |          52,50 $ |
----------------------------------------------------
| Peter         | K             |         800,00 $ |
----------------------------------------------------
| Anna          | A             |         736,00 $ |
----------------------------------------------------
| Amritansh     | BB            |         230,00 $ |
----------------------------------------------------
| Sven          | I             |          96,50 $ |
----------------------------------------------------
| Francisco     | F             |         510,00 $ |
----------------------------------------------------
| Elizabeth     | H             |         510,00 $ |
----------------------------------------------------
| John          | Y             |         660,00 $ |
----------------------------------------------------
| Run           | Z             |       2 250,00 $ |
----------------------------------------------------
| Soo           | CC            |       1 560,00 $ |
----------------------------------------------------
| Francisco     | F             |         900,00 $ |
----------------------------------------------------
| Francisco     | F             |       1 590,00 $ |
----------------------------------------------------
| Christina     | D             |         380,00 $ |
----------------------------------------------------
| Thomas        | C             |           0,00 $ |
----------------------------------------------------
| Thomas        | C             |           0,00 $ |
----------------------------------------------------
#+END_SRC

** End file
#+BEGIN_SRC 
|  Custship |Cust|Extended Price|
---------------------------------
| Karen     | AA |   1 400,00 € |
| Karen     | AA |     105,00 € |
| Christina | D  |     300,00 € |
| Christina | D  |     530,00 € |
| Christina | D  |      35,00 € |
| John      | L  |     270,00 € |
| John      | L  |     920,00 € |
| Elizabeth | H  |     276,00 € |
| Christina | D  |     184,00 € |
| Soo       | CC |     127,50 € |
| Thomas    | C  |   1 930,00 € |
| Francisco | F  |     680,00 € |
| Amritansh | BB |  13 800,00 € |
| Elizabeth | H  |   1 275,00 € |
| Roland    | J  |     598,00 € |
| Ming-Yang | G  |  13 800,00 € |
| Roland    | J  |     250,00 € |
| Roland    | J  |     220,00 € |
| Roland    | J  |      92,00 € |
| Peter     | K  |      70,00 € |
| Peter     | K  |     149,50 € |
| Anna      | A  |     450,00 € |
| Anna      | A  |   1 150,00 € |
| Anna      | A  |      74,75 € |
| Amritansh | BB |     482,50 € |
| Amritansh | BB |     920,00 € |
| Sven      | I  |   1 950,00 € |
| Sven      | I  |   1 740,00 € |
| Francisco | F  |   4 200,00 € |
| Elizabeth | H  |   1 000,00 € |
| Elizabeth | H  |     230,00 € |
| John      | Y  |     200,00 € |
| Run       | Z  |     533,75 € |
| Run       | Z  |     289,50 € |
| Run       | Z  |     552,00 € |
| Soo       | CC |   1 218,00 € |
| Francisco | F  |     127,50 € |
| Karen     | AA |              |
| Christina | D  |   3 240,00 € |
| Christina | D  |     280,00 € |
| John      | L  |              |
| Elizabeth | H  |   1 392,00 € |
| Christina | D  |              |
| Soo       | CC |              |
| Thomas    | C  |     500,00 € |
| Thomas    | C  |     120,00 € |
| Francisco | F  |              |
| Amritansh | BB |              |
| Elizabeth | H  |              |
| Roland    | J  |     200,00 € |
| Ming-Yang | G  |              |
| Roland    | J  |      52,50 € |
| Peter     | K  |     800,00 € |
| Anna      | A  |     736,00 € |
| Amritansh | BB |     230,00 € |
| Sven      | I  |      96,50 € |
| Francisco | F  |     510,00 € |
| Elizabeth | H  |     510,00 € |
| John      | Y  |     660,00 € |
| Run       | Z  |   2 250,00 € |
| Soo       | CC |   1 560,00 € |
| Francisco | F  |     900,00 € |
| Francisco | F  |   1 590,00 € |
| Christina | D  |     380,00 € |
| Thomas    | C  |       0,00 € |
| Thomas    | C  |       0,00 € |
---------------------------------
#+END_SRC

* Sort by sum of numbers in a line(?)

The lines with the biggest sums need to be at the top. The sums are on the right, which makes life hard. Maybe you can find a feature that will do all the work for you...
** Start file
#+BEGIN_SRC 
8635147+876+5597+1686+54=8643360
2415+382376+88324+81544+926+68619475+677+222852=69398589
80+21+4478882+8945092=13424075
62+9598=9660
16832904+537+51460155+6822+2+4901436+47443+5669+855928+8113549+424282=82648727
33+9872=9905
555839
5017598+5639262+4+62+9413+4+4991+41568=10712902
4977+164+77+1018643+593851+83730=1701442
220+6831+26=7077
5+54102+1034451=1088558
37844
1
35+2983325+0+6400=2989760
8081+8361365+6+477=8369929
66+68232+9406935+6489662=15964895
6569+59336692+75+11328=59354664
28332+725+2683+45913425+9648987+4911=55599063
69724687+8+7+9940+5568+29585+518916=70288711
1804642
659157+5144361+7072+16+4799+811+58742059+451875+138174=65148324
2288508+509472+43+83704=2881727
872027+1115415+1+47922+547008+56+5550+71642773+948394=75179146
142
#+END_SRC

** End file
#+BEGIN_SRC 
16832904+537+51460155+6822+2+4901436+47443+5669+855928+8113549+424282=82648727
872027+1115415+1+47922+547008+56+5550+71642773+948394=75179146
69724687+8+7+9940+5568+29585+518916=70288711
2415+382376+88324+81544+926+68619475+677+222852=69398589
659157+5144361+7072+16+4799+811+58742059+451875+138174=65148324
6569+59336692+75+11328=59354664
28332+725+2683+45913425+9648987+4911=55599063
66+68232+9406935+6489662=15964895
80+21+4478882+8945092=13424075
5017598+5639262+4+62+9413+4+4991+41568=10712902
8635147+876+5597+1686+54=8643360
8081+8361365+6+477=8369929
35+2983325+0+6400=2989760
2288508+509472+43+83704=2881727
1804642
4977+164+77+1018643+593851+83730=1701442
5+54102+1034451=1088558
555839
37844
33+9872=9905
62+9598=9660
220+6831+26=7077
142
1
#+END_SRC

* Presidential Sorting

Given a nice CSV formatted arrangement of the Presidents of the United States, we need to print out an alphabetical list in pretty columns. Prove that vim can conquer this basic Excel task!
** Start file
#+BEGIN_SRC 
President,Political Party,Dates in Office
George Washington,,1789_97
John Adams,Federalist,1797_1801
Thomas Jefferson,Democratic-Republican,1801_9
James Madison,Democratic-Republican,1809_17
James Monroe,Democratic-Republican,1817_25
John Quincy Adams,Democratic-Republican,1825_29
Andrew Jackson,Democratic,1829_37
Martin Van Buren,Democratic,1837_41
William Henry Harrison,Whig,1841
John Tyler,Whig,1841_45
James Knox Polk,Democratic,1845_49
Zachary Taylor,Whig,1849_50
Millard Fillmore,Whig,1850_53
Franklin Pierce,Democratic,1853_57
James Buchanan,Democratic,1857_61
Abraham Lincoln,Republican,1861_65
Andrew Johnson,Democratic/National Union,1865_69
Ulysses Simpson Grant,Republican,1869_77
Rutherford Birchard Hayes,Republican,1877_81
James Abram Garfield,Republican,1881
Chester Alan Arthur,Republican,1881_85
Grover Cleveland,Democratic,1885_89
Benjamin Harrison,Republican,1889_93
Grover Cleveland,Democratic,1893_97
William McKinley,Republican,1897_1901
Theodore Roosevelt,Republican,1901_9
William Howard Taft,Republican,1909_13
Woodrow Wilson,Democratic,1913_21
Warren Gamaliel Harding,Republican,1921_23
Calvin Coolidge,Republican,1923_29
Herbert Clark Hoover,Republican,1929_33
Franklin Delano Roosevelt,Democratic,1933_45
Harry S. Truman,Democratic,1945_53
Dwight David Eisenhower,Republican,1953_61
John Fitzgerald Kennedy,Democratic,1961_63
Lyndon Baines Johnson,Democratic,1963_69
Richard Milhous Nixon,Republican,1969_74
Gerald Rudolph Ford,Republican,1974_77
Jimmy Carter,Democratic,1977_81
Ronald Wilson Reagan,Republican,1981_89
George Herbert Walker Bush,Republican,1989_93
Bill Clinton,Democratic,1993_2001
George Walker Bush,Republican,2001_9
Barack Hussein Obama,Democratic,2009_
#+END_SRC

** End file
#+BEGIN_SRC 
President                   Political Party            Dates in Office
Abraham Lincoln             Republican                 1861–65
Andrew Jackson              Democratic                 1829–37
Andrew Johnson              Democratic/National Union  1865–69
Barack Hussein Obama        Democratic                 2009–
Benjamin Harrison           Republican                 1889–93
Bill Clinton                Democratic                 1993–2001
Calvin Coolidge             Republican                 1923–29
Chester Alan Arthur         Republican                 1881–85
Dwight David Eisenhower     Republican                 1953–61
Franklin Delano Roosevelt   Democratic                 1933–45
Franklin Pierce             Democratic                 1853–57
George Herbert Walker Bush  Republican                 1989–93
George Walker Bush          Republican                 2001–9
George Washington                                      1789–97
Gerald Rudolph Ford         Republican                 1974–77
Grover Cleveland            Democratic                 1885–89
Grover Cleveland            Democratic                 1893–97
Harry S. Truman             Democratic                 1945–53
Herbert Clark Hoover        Republican                 1929–33
James Abram Garfield        Republican                 1881
James Buchanan              Democratic                 1857–61
James Knox Polk             Democratic                 1845–49
James Madison               Democratic-Republican      1809–17
James Monroe                Democratic-Republican      1817–25
Jimmy Carter                Democratic                 1977–81
John Adams                  Federalist                 1797–1801
John Fitzgerald Kennedy     Democratic                 1961–63
John Quincy Adams           Democratic-Republican      1825–29
John Tyler                  Whig                       1841–45
Lyndon Baines Johnson       Democratic                 1963–69
Martin Van Buren            Democratic                 1837–41
Millard Fillmore            Whig                       1850–53
Richard Milhous Nixon       Republican                 1969–74
Ronald Wilson Reagan        Republican                 1981–89
Rutherford Birchard Hayes   Republican                 1877–81
Theodore Roosevelt          Republican                 1901–9
Thomas Jefferson            Democratic-Republican      1801–9
Ulysses Simpson Grant       Republican                 1869–77
Warren Gamaliel Harding     Republican                 1921–23
William Henry Harrison      Whig                       1841
William Howard Taft         Republican                 1909–13
William McKinley            Republican                 1897–1901
Woodrow Wilson              Democratic                 1913–21
Zachary Taylor              Whig                       1849–50
#+END_SRC

* Lenny Spiral

Make one lenny into an infinite army of lennys.
** Start file
#+BEGIN_SRC 
(   ͡° ͜ʖ ͡° )
#+END_SRC

** End file
#+BEGIN_SRC 
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡° )  ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ ͡° )° ͜ʖ ͡° )
   (   ͡° ͜ʖ ͡° )ʖ ͡° )
    (   ͡° ͜ʖ ͡° )° )
     (   ͡° ͜ʖ ͡° ))
     ((   ͡° ͜ʖ ͡° )
    (  (   ͡° ͜ʖ ͡° )
   (   ͡°(   ͡° ͜ʖ ͡° )
  (   ͡° ͜ʖ(   ͡° ͜ʖ ͡° )
 (   ͡° ͜ʖ ͡°(   ͡° ͜ʖ ͡° )
(   ͡° ͜ʖ ͡° )(   ͡° ͜ʖ ͡° )
#+END_SRC

* maximun and minimun

Find the maximum and minimum of the rows.
** Start file
#+BEGIN_SRC 
[14, 30, 21, 5, 13, 9, 66, 27, 34, 24, 52, 9, 2, 12, 0, 18, 5, 6, 4, 19]
[23, 15, 5, 11, 17, 13, 12, 6, 9, 49, 3, 15, 16, 16, 11, 9, 12, 6, 11, 8]
[27, 11, 9, 18, 20, 10, 6, 50, 6, 26, 45, 12, 15, 29, 12, 13, 17, 29, 12, 97]
[27, 17, 28, 24, 10, 89, 37, 55, 43, 35, 7, 40, 36, 46, 9, 53, 9, 6, 14, 15]
[370, 267, 464, 600]
[12, 29, 17, 26, 13, 17, 28, 13, 22, 27, 49, 6, 8, 16, 2, 16, 0, 14, 6, 9]
[5, 19, 10, 28, 24, 18, 11, 16, 6, 17, 47, 10, 11, 53, 18, 4, 66, 7, 13, 5]
[18, 30, 29, 18, 25, 24, 10, 33, 35, 15, 49, 22, 20, 10, 10, 30, 22, 33, 12, 88]
[18, 22, 17, 11, 17, 8, 9, 47, 48, 39, 24, 4, 67, 31, 23, 12, 25, 12, 22, 26]
[330, 388, 533, 482]
[13, 13, 26, 43, 10, 15, 50, 19, 27, 17, 11, 3, 6, 18, 2, 20, 1, 10, 8, 19]
[8, 13, 4, 26, 3, 5, 11, 9, 10, 8, 34, 42, 7, 42, 11, 13, 75, 11, 5, 7]
[12, 36, 57, 26, 39, 20, 11, 4, 17, 13, 9, 42, 9, 5, 20, 28, 30, 26, 12, 27]
[12, 31, 21, 21, 26, 43, 18, 46, 58, 8, 25, 10, 51, 72, 34, 24, 25, 16, 28, 22]
[331, 344, 443, 591]
[16, 15, 20, 39, 14, 10, 29, 43, 11, 21, 3, 13, 3, 9, 3, 17, 1, 23, 18, 12]
[13, 10, 18, 9, 7, 22, 6, 17, 17, 14, 12, 57, 9, 45, 10, 13, 15, 23, 7, 10]
[19, 34, 63, 22, 19, 17, 32, 5, 5, 11, 25, 25, 14, 15, 23, 29, 25, 12, 7, 31]
[19, 27, 25, 20, 14, 44, 14, 27, 42, 40, 26, 19, 32, 73, 42, 7, 22, 43, 30, 33]
[320, 334, 433, 599]
[9, 8, 46, 21, 28, 11, 33, 22, 13, 16, 12, 10, 4, 10, 3, 4, 2, 15, 4, 22]
[29, 13, 9, 4, 16, 13, 9, 12, 24, 18, 3, 31, 39, 39, 21, 12, 22, 11, 21, 7]
[18, 11, 10, 15, 37, 19, 19, 19, 18, 15, 38, 22, 14, 14, 18, 34, 21, 48, 19, 36]
[18, 25, 10, 20, 18, 15, 16, 22, 26, 40, 21, 32, 12, 11, 18, 21, 16, 29, 40, 4]
[293, 353, 445, 414]
[14, 16, 39, 24, 30, 10, 28, 11, 17, 20, 33, 29, 2, 8, 0, 14, 3, 9, 2, 12]
[13, 20, 11, 13, 12, 15, 11, 4, 9, 23, 27, 10, 53, 50, 14, 17, 48, 16, 22, 0]
[9, 35, 22, 10, 26, 20, 26, 46, 18, 17, 46, 10, 10, 11, 29, 17, 19, 31, 51, 81]
[9, 24, 31, 31, 37, 19, 32, 16, 19, 29, 20, 22, 57, 43, 7, 32, 11, 15, 48, 16]
[321, 388, 534, 518]
[42, 3, 33, 52, 11, 16, 15, 40, 27, 12, 34, 37, 6, 27, 0, 6, 3, 29, 3, 10]
[18, 6, 14, 15, 10, 24, 8, 4, 8, 28, 5, 15, 24, 35, 4, 15, 63, 13, 11, 7]
[8, 11, 47, 11, 13, 43, 17, 14, 10, 7, 18, 9, 47, 20, 27, 20, 26, 18, 42, 41]
[8, 44, 14, 42, 47, 28, 22, 26, 38, 8, 34, 55, 29, 22, 46, 38, 21, 28, 51, 15]
[406, 327, 449, 616]
[15, 48, 31, 32, 40, 60, 54, 148, 163, 227, 249, 295, 335, 346, 361, 352, 385, 395, 404, 390]
[9, 24, 13, 10, 62, 15, 10, 5, 5, 37, 33, 146, 108, 20, 5, 11, 132, 146, 23, 19]
[18, 190, 213, 185, 243, 31, 162, 152, 28, 297, 119, 83, 66, 155, 74, 186, 15, 258, 164, 129]
[18, 115, 199, 202, 240, 91, 273, 221, 317, 324, 316, 363, 185, 357, 199, 176, 11, 123, 84, 90]
[4330, 833, 2768, 3904]
#+END_SRC

** End file
#+BEGIN_SRC 
[14, 30, 21, 5, 13, 9, 66, 27, 34, 24, 52, 9, 2, 12, 0, 18, 5, 6, 4, 19]                             0  <>  66
[23, 15, 5, 11, 17, 13, 12, 6, 9, 49, 3, 15, 16, 16, 11, 9, 12, 6, 11, 8]                            3  <>  49
[27, 11, 9, 18, 20, 10, 6, 50, 6, 26, 45, 12, 15, 29, 12, 13, 17, 29, 12, 97]                        6  <>  97
[27, 17, 28, 24, 10, 89, 37, 55, 43, 35, 7, 40, 36, 46, 9, 53, 9, 6, 14, 15]                         6  <>  89
[370, 267, 464, 600]                                                                               267  <>  600
[12, 29, 17, 26, 13, 17, 28, 13, 22, 27, 49, 6, 8, 16, 2, 16, 0, 14, 6, 9]                           0  <>  49
[5, 19, 10, 28, 24, 18, 11, 16, 6, 17, 47, 10, 11, 53, 18, 4, 66, 7, 13, 5]                          4  <>  66
[18, 30, 29, 18, 25, 24, 10, 33, 35, 15, 49, 22, 20, 10, 10, 30, 22, 33, 12, 88]                    10  <>  88
[18, 22, 17, 11, 17, 8, 9, 47, 48, 39, 24, 4, 67, 31, 23, 12, 25, 12, 22, 26]                        4  <>  67
[330, 388, 533, 482]                                                                               330  <>  533
[13, 13, 26, 43, 10, 15, 50, 19, 27, 17, 11, 3, 6, 18, 2, 20, 1, 10, 8, 19]                          1  <>  50
[8, 13, 4, 26, 3, 5, 11, 9, 10, 8, 34, 42, 7, 42, 11, 13, 75, 11, 5, 7]                              3  <>  75
[12, 36, 57, 26, 39, 20, 11, 4, 17, 13, 9, 42, 9, 5, 20, 28, 30, 26, 12, 27]                         4  <>  57
[12, 31, 21, 21, 26, 43, 18, 46, 58, 8, 25, 10, 51, 72, 34, 24, 25, 16, 28, 22]                      8  <>  72
[331, 344, 443, 591]                                                                               331  <>  591
[16, 15, 20, 39, 14, 10, 29, 43, 11, 21, 3, 13, 3, 9, 3, 17, 1, 23, 18, 12]                          1  <>  43
[13, 10, 18, 9, 7, 22, 6, 17, 17, 14, 12, 57, 9, 45, 10, 13, 15, 23, 7, 10]                          6  <>  57
[19, 34, 63, 22, 19, 17, 32, 5, 5, 11, 25, 25, 14, 15, 23, 29, 25, 12, 7, 31]                        5  <>  63
[19, 27, 25, 20, 14, 44, 14, 27, 42, 40, 26, 19, 32, 73, 42, 7, 22, 43, 30, 33]                      7  <>  73
[320, 334, 433, 599]                                                                               320  <>  599
[9, 8, 46, 21, 28, 11, 33, 22, 13, 16, 12, 10, 4, 10, 3, 4, 2, 15, 4, 22]                            2  <>  46
[29, 13, 9, 4, 16, 13, 9, 12, 24, 18, 3, 31, 39, 39, 21, 12, 22, 11, 21, 7]                          3  <>  39
[18, 11, 10, 15, 37, 19, 19, 19, 18, 15, 38, 22, 14, 14, 18, 34, 21, 48, 19, 36]                    10  <>  48
[18, 25, 10, 20, 18, 15, 16, 22, 26, 40, 21, 32, 12, 11, 18, 21, 16, 29, 40, 4]                      4  <>  40
[293, 353, 445, 414]                                                                               293  <>  445
[14, 16, 39, 24, 30, 10, 28, 11, 17, 20, 33, 29, 2, 8, 0, 14, 3, 9, 2, 12]                           0  <>  39
[13, 20, 11, 13, 12, 15, 11, 4, 9, 23, 27, 10, 53, 50, 14, 17, 48, 16, 22, 0]                        0  <>  53
[9, 35, 22, 10, 26, 20, 26, 46, 18, 17, 46, 10, 10, 11, 29, 17, 19, 31, 51, 81]                      9  <>  81
[9, 24, 31, 31, 37, 19, 32, 16, 19, 29, 20, 22, 57, 43, 7, 32, 11, 15, 48, 16]                       7  <>  57
[321, 388, 534, 518]                                                                               321  <>  534
[42, 3, 33, 52, 11, 16, 15, 40, 27, 12, 34, 37, 6, 27, 0, 6, 3, 29, 3, 10]                           0  <>  52
[18, 6, 14, 15, 10, 24, 8, 4, 8, 28, 5, 15, 24, 35, 4, 15, 63, 13, 11, 7]                            4  <>  63
[8, 11, 47, 11, 13, 43, 17, 14, 10, 7, 18, 9, 47, 20, 27, 20, 26, 18, 42, 41]                        7  <>  47
[8, 44, 14, 42, 47, 28, 22, 26, 38, 8, 34, 55, 29, 22, 46, 38, 21, 28, 51, 15]                       8  <>  55
[406, 327, 449, 616]                                                                               327  <>  616
[15, 48, 31, 32, 40, 60, 54, 148, 163, 227, 249, 295, 335, 346, 361, 352, 385, 395, 404, 390]       15  <>  404
[9, 24, 13, 10, 62, 15, 10, 5, 5, 37, 33, 146, 108, 20, 5, 11, 132, 146, 23, 19]                     5  <>  146
[18, 190, 213, 185, 243, 31, 162, 152, 28, 297, 119, 83, 66, 155, 74, 186, 15, 258, 164, 129]       15  <>  297
[18, 115, 199, 202, 240, 91, 273, 221, 317, 324, 316, 363, 185, 357, 199, 176, 11, 123, 84, 90]     11  <>  363
[4330, 833, 2768, 3904]                                                                            833  <>  4330
#+END_SRC

* Simple Maths

Not much to say, discover by yourself!
** Start file
#+BEGIN_SRC 
1
37
456
1013
498934
26456821
1658
168813
3574
6557
815
147
65465456
#+END_SRC

** End file
#+BEGIN_SRC 
41
12
14
23
19
27
20
34
37
5
15
10
1
#+END_SRC

* Under the cupola

Taking some liberty about the name and plot of the Stephen King's famous novel (and TV series) to make this challenge. Are you able to recreate graphically the key phrase of the story? (I think is gonna be hard!)
** Start file
#+BEGIN_SRC 
The pink stars are falling in lines
#+END_SRC

** End file
#+BEGIN_SRC 
T   p    s     a   f       i  l
 h   i    t     r   a       n  i
  e   n    a     e   l          n
       k    r         l          e
             s         i          s
                        n
                         g
#+END_SRC

* Sort by your own sum

Same numbers as last time, but you'll have to add them yourself.
** Start file
#+BEGIN_SRC 
8635147+876+5597+1686+54
2415+382376+88324+81544+926+68619475+677+222852
80+21+4478882+8945092
62+9598
16832904+537+51460155+6822+2+4901436+47443+5669+855928+8113549+424282
33+9872
555839
5017598+5639262+4+62+9413+4+4991+41568
4977+164+77+1018643+593851+83730
220+6831+26
5+54102+1034451
37844
1
35+2983325+0+6400
8081+8361365+6+477
66+68232+9406935+6489662
6569+59336692+75+11328
28332+725+2683+45913425+9648987+4911
69724687+8+7+9940+5568+29585+518916
1804642
659157+5144361+7072+16+4799+811+58742059+451875+138174
2288508+509472+43+83704
872027+1115415+1+47922+547008+56+5550+71642773+948394
142
#+END_SRC

** End file
#+BEGIN_SRC 
16832904+537+51460155+6822+2+4901436+47443+5669+855928+8113549+424282
872027+1115415+1+47922+547008+56+5550+71642773+948394
69724687+8+7+9940+5568+29585+518916
2415+382376+88324+81544+926+68619475+677+222852
659157+5144361+7072+16+4799+811+58742059+451875+138174
6569+59336692+75+11328
28332+725+2683+45913425+9648987+4911
66+68232+9406935+6489662
80+21+4478882+8945092
5017598+5639262+4+62+9413+4+4991+41568
8635147+876+5597+1686+54
8081+8361365+6+477
35+2983325+0+6400
2288508+509472+43+83704
1804642
4977+164+77+1018643+593851+83730
5+54102+1034451
555839
37844
33+9872
62+9598
220+6831+26
142
1
#+END_SRC

* XML to JSON

Convert this xml file into json.
** Start file
#+BEGIN_SRC 
<?xml version="1.0"?>
<catalog>
   <book id="bk101">
      <author>Gambardella, Matthew</author>
      <title>XML Developer's Guide</title>
      <genre>Computer</genre>
      <price>44.95</price>
      <publish_date>2000-10-01</publish_date>
      <description>An in-depth look at creating applications 
      with XML.</description>
   </book>
   <book id="bk102">
      <author>Ralls, Kim</author>
      <title>Midnight Rain</title>
      <genre>Fantasy</genre>
      <price>5.95</price>
      <publish_date>2000-12-16</publish_date>
      <description>A former architect battles corporate zombies, 
      an evil sorceress, and her own childhood to become queen 
      of the world.</description>
   </book>
   <book id="bk103">
      <author>Corets, Eva</author>
      <title>Maeve Ascendant</title>
      <genre>Fantasy</genre>
      <price>5.95</price>
      <publish_date>2000-11-17</publish_date>
      <description>After the collapse of a nanotechnology 
      society in England, the young survivors lay the 
      foundation for a new society.</description>
   </book>
   <book id="bk104">
      <author>Corets, Eva</author>
      <title>Oberon's Legacy</title>
      <genre>Fantasy</genre>
      <price>5.95</price>
      <publish_date>2001-03-10</publish_date>
      <description>In post-apocalypse England, the mysterious 
      agent known only as Oberon helps to create a new life 
      for the inhabitants of London. Sequel to Maeve 
      Ascendant.</description>
   </book>
   <book id="bk105">
      <author>Corets, Eva</author>
      <title>The Sundered Grail</title>
      <genre>Fantasy</genre>
      <price>5.95</price>
      <publish_date>2001-09-10</publish_date>
      <description>The two daughters of Maeve, half-sisters, 
      battle one another for control of England. Sequel to 
      Oberon's Legacy.</description>
   </book>
   <book id="bk106">
      <author>Randall, Cynthia</author>
      <title>Lover Birds</title>
      <genre>Romance</genre>
      <price>4.95</price>
      <publish_date>2000-09-02</publish_date>
      <description>When Carla meets Paul at an ornithology 
      conference, tempers fly as feathers get ruffled.</description>
   </book>
   <book id="bk107">
      <author>Thurman, Paula</author>
      <title>Splish Splash</title>
      <genre>Romance</genre>
      <price>4.95</price>
      <publish_date>2000-11-02</publish_date>
      <description>A deep sea diver finds true love twenty 
      thousand leagues beneath the sea.</description>
   </book>
   <book id="bk108">
      <author>Knorr, Stefan</author>
      <title>Creepy Crawlies</title>
      <genre>Horror</genre>
      <price>4.95</price>
      <publish_date>2000-12-06</publish_date>
      <description>An anthology of horror stories about roaches,
      centipedes, scorpions  and other insects.</description>
   </book>
   <book id="bk109">
      <author>Kress, Peter</author>
      <title>Paradox Lost</title>
      <genre>Science Fiction</genre>
      <price>6.95</price>
      <publish_date>2000-11-02</publish_date>
      <description>After an inadvertant trip through a Heisenberg
      Uncertainty Device, James Salway discovers the problems 
      of being quantum.</description>
   </book>
   <book id="bk110">
      <author>O'Brien, Tim</author>
      <title>Microsoft .NET: The Programming Bible</title>
      <genre>Computer</genre>
      <price>36.95</price>
      <publish_date>2000-12-09</publish_date>
      <description>Microsoft's .NET initiative is explored in 
      detail in this deep programmer's reference.</description>
   </book>
   <book id="bk111">
      <author>O'Brien, Tim</author>
      <title>MSXML3: A Comprehensive Guide</title>
      <genre>Computer</genre>
      <price>36.95</price>
      <publish_date>2000-12-01</publish_date>
      <description>The Microsoft MSXML3 parser is covered in 
      detail, with attention to XML DOM interfaces, XSLT processing, 
      SAX and more.</description>
   </book>
   <book id="bk112">
      <author>Galos, Mike</author>
      <title>Visual Studio 7: A Comprehensive Guide</title>
      <genre>Computer</genre>
      <price>49.95</price>
      <publish_date>2001-04-16</publish_date>
      <description>Microsoft Visual Studio 7 is explored in depth,
      looking at how Visual Basic, Visual C++, C#, and ASP+ are 
      integrated into a comprehensive development 
      environment.</description>
   </book>
</catalog>
#+END_SRC

** End file
#+BEGIN_SRC 
[{ "id": "bk101",
   "author": "Gambardella, Matthew",
   "title": "XML Developer's Guide",
   "genre": "Computer",
   "price": 44.95,
   "publish_date": "2000-10-01",
   "description": "An in-depth look at creating applications with XML." },
 { "id": "bk102",
   "author": "Ralls, Kim",
   "title": "Midnight Rain",
   "genre": "Fantasy",
   "price": 5.95,
   "publish_date": "2000-12-16",
   "description": "A former architect battles corporate zombies, an evil sorceress, and her own childhood to become queen of the world." },
 { "id": "bk103",
   "author": "Corets, Eva",
   "title": "Maeve Ascendant",
   "genre": "Fantasy",
   "price": 5.95,
   "publish_date": "2000-11-17",
   "description": "After the collapse of a nanotechnology society in England, the young survivors lay the foundation for a new society." },
 { "id": "bk104",
   "author": "Corets, Eva",
   "title": "Oberon's Legacy",
   "genre": "Fantasy",
   "price": 5.95,
   "publish_date": "2001-03-10",
   "description": "In post-apocalypse England, the mysterious agent known only as Oberon helps to create a new life for the inhabitants of London. Sequel to Maeve Ascendant." },
 { "id": "bk105",
   "author": "Corets, Eva",
   "title": "The Sundered Grail",
   "genre": "Fantasy",
   "price": 5.95,
   "publish_date": "2001-09-10",
   "description": "The two daughters of Maeve, half-sisters, battle one another for control of England. Sequel to Oberon's Legacy." },
 { "id": "bk106",
   "author": "Randall, Cynthia",
   "title": "Lover Birds",
   "genre": "Romance",
   "price": 4.95,
   "publish_date": "2000-09-02",
   "description": "When Carla meets Paul at an ornithology conference, tempers fly as feathers get ruffled." },
 { "id": "bk107",
   "author": "Thurman, Paula",
   "title": "Splish Splash",
   "genre": "Romance",
   "price": 4.95,
   "publish_date": "2000-11-02",
   "description": "A deep sea diver finds true love twenty thousand leagues beneath the sea." },
 { "id": "bk108",
   "author": "Knorr, Stefan",
   "title": "Creepy Crawlies",
   "genre": "Horror",
   "price": 4.95,
   "publish_date": "2000-12-06",
   "description": "An anthology of horror stories about roaches, centipedes, scorpions  and other insects." },
 { "id": "bk109",
   "author": "Kress, Peter",
   "title": "Paradox Lost",
   "genre": "Science Fiction",
   "price": 6.95,
   "publish_date": "2000-11-02",
   "description": "After an inadvertant trip through a Heisenberg Uncertainty Device, James Salway discovers the problems of being quantum." },
 { "id": "bk110",
   "author": "O'Brien, Tim",
   "title": "Microsoft .NET: The Programming Bible",
   "genre": "Computer",
   "price": 36.95,
   "publish_date": "2000-12-09",
   "description": "Microsoft's .NET initiative is explored in detail in this deep programmer's reference." },
 { "id": "bk111",
   "author": "O'Brien, Tim",
   "title": "MSXML3: A Comprehensive Guide",
   "genre": "Computer",
   "price": 36.95,
   "publish_date": "2000-12-01",
   "description": "The Microsoft MSXML3 parser is covered in detail, with attention to XML DOM interfaces, XSLT processing, SAX and more." },
 { "id": "bk112",
   "author": "Galos, Mike",
   "title": "Visual Studio 7: A Comprehensive Guide",
   "genre": "Computer",
   "price": 49.95,
   "publish_date": "2001-04-16",
   "description": "Microsoft Visual Studio 7 is explored in depth, looking at how Visual Basic, Visual C++, C#, and ASP+ are integrated into a comprehensive development environment." }]
#+END_SRC

* Fibonacci Triangles

Triangles
** Start file
#+BEGIN_SRC 
123 5  8   13      21           34                   55                                89
#+END_SRC

** End file
#+BEGIN_SRC 
                                                                                        |
                                                                                       /|
                                                                                      / |
                                                                                     /  |
                                                                                    /   |
                                                                                   /    |
                                                                                  /     |
                                                                                 /      |
                                                                                /       |
                                                                               /        |
                                                                              /         |
                                                                             /          |
                                                                            /           |
                                                                           /            |
                                                                          /             |
                                                                         /              |
                                                                        /               |
                                                                       /                |
                                                                      /                 |
                                                                     /                  |
                                                                    /                   |
                                                                   /                    |
                                                                  /                     |
                                                                 /                      |
                                                                /                       |
                                                               /                        |
                                                              /                         |
                                                             /                          |
                                                            /                           |
                                                           /                            |
                                                          /                             |
                                                         /                              |
                                                        /                               |
                                                       /                                |
                                                      /                                 |
                                                     /|                                 |
                                                    / |                                 |
                                                   /  |                                 |
                                                  /   |                                 |
                                                 /    |                                 |
                                                /     |                                 |
                                               /      |                                 |
                                              /       |                                 |
                                             /        |                                 |
                                            /         |                                 |
                                           /          |                                 |
                                          /           |                                 |
                                         /            |                                 |
                                        /             |                                 |
                                       /              |                                 |
                                      /               |                                 |
                                     /                |                                 |
                                    /                 |                                 |
                                   /                  |                                 |
                                  /                   |                                 |
                                 /                    |                                 |
                                /|                    |                                 |
                               / |                    |                                 |
                              /  |                    |                                 |
                             /   |                    |                                 |
                            /    |                    |                                 |
                           /     |                    |                                 |
                          /      |                    |                                 |
                         /       |                    |                                 |
                        /        |                    |                                 |
                       /         |                    |                                 |
                      /          |                    |                                 |
                     /           |                    |                                 |
                    /            |                    |                                 |
                   /|            |                    |                                 |
                  / |            |                    |                                 |
                 /  |            |                    |                                 |
                /   |            |                    |                                 |
               /    |            |                    |                                 |
              /     |            |                    |                                 |
             /      |            |                    |                                 |
            /       |            |                    |                                 |
           /|       |            |                    |                                 |
          / |       |            |                    |                                 |
         /  |       |            |                    |                                 |
        /   |       |            |                    |                                 |
       /    |       |            |                    |                                 |
      /|    |       |            |                    |                                 |
     / |    |       |            |                    |                                 |
    /  |    |       |            |                    |                                 |
   /|  |    |       |            |                    |                                 |
  / |  |    |       |            |                    |                                 |
 /| |  |    |       |            |                    |                                 |
123-5--8---13------21-----------34-------------------55--------------------------------89
#+END_SRC

* range(10) digit rotation

This is a data generator challenge or some kind of gift..
** Start file
#+BEGIN_SRC 
 0 1 2 3 4 5 * 7 8 9
 1 2 3 4 5 6 * 8 9 0
 2 3 4 5 6 7 * 9 0 1
 3 4 5 6 7 8 * 0 1 2
 4 5 6 7 8 9 * 1 2 3
 5 6 7 8 9 0 * 2 3 4
 * * * * * * * * * *
 7 8 9 0 1 2 * 4 5 6
 8 9 0 1 2 3 * 5 6 7
 9 0 1 2 3 4 * 6 7 8
#+END_SRC

** End file
#+BEGIN_SRC 
 0 1 2 3 4 * 6 7 8 9
 1 2 3 4 * 6 7 8 9 0
 2 3 4 * 6 7 8 9 0 1
 3 4 * 6 7 8 9 0 1 2
 4 * 6 7 8 9 0 1 2 3
 * 6 7 8 9 0 1 2 3 4
 6 7 8 9 0 1 2 3 4 *
 7 8 9 0 1 2 3 4 * 6
 8 9 0 1 2 3 4 * 6 7
 9 0 1 2 3 4 * 6 7 8
#+END_SRC

* Sort with uniq OpenEmbedded package names

For each line take 4th dirname of path. For example: "alsa-utils", "gawk-3.1.5", ... But! But if previous result is "files", take 3rd dirname instead. For example: "mktemp", "mklibs" ... If version is present in package name (dash is the separator character), take it. For example: "apt-0.9.9.4" prevails over "apt". And finally, use sort -u to get unique names!
** Start file
#+BEGIN_SRC 
meta/recipes-devtools/qemu/qemu/fix-libcap-header-issue-on-some-distro.patch
meta/recipes-devtools/qemu/qemu/larger_default_ram_size.patch
meta/recipes-multimedia/alsa/alsa-utils/0001-alsactl-don-t-let-systemd-unit-restore-the-volume-wh.patch
meta/recipes-devtools/apt/apt-0.9.9.4/no-ko-translation.patch
meta/recipes-extended/cracklib/cracklib/0001-packlib.c-support-dictionary-byte-order-dependent.patch
meta/recipes-extended/screen/screen/rpathfix.patch
meta/recipes-extended/lighttpd/lighttpd/acdefine.patch
meta/recipes-extended/cracklib/cracklib/0002-craklib-fix-testnum-and-teststr-failed.patch
meta/recipes-multimedia/tremor/tremor-20120314/obsolete_automake_macros.patch
meta/recipes-devtools/flex/files/do_not_create_pdf_doc.patch
meta/recipes-extended/gawk/gawk-3.1.5/obsolete_automake_macros.patch
meta/recipes-extended/mktemp/files/fix-parallel-make.patch
meta/recipes-extended/screen/screen-4.0.3/configure.patch
meta/recipes-extended/gawk/gawk-4.1.1/Use-DESTDIR-in-extension-Makefile.am-when-removing-..patch
meta/recipes-devtools/qemu/qemu/configure-Fix-Darwin-target-detection.patch
meta/recipes-devtools/mklibs/files/sysrooted-ldso.patch
meta/recipes-extended/gawk/gawk-4.1.1/extension-Add-DESTDIR-prefix-to-remaining-pkgextensi.patch
meta/recipes-devtools/qemu/files/qemu-enlarge-env-entry-size.patch
meta/recipes-graphics/drm/libdrm/installtests-and-use-vimgolf.patch
meta/recipes-extended/lighttpd/lighttpd/pkgconfig.patch
meta/recipes-devtools/m4/m4/program_prefix.patch
meta/recipes-devtools/qemu/files/exclude-some-arm-EABI-obsolete-syscalls.patch
meta/recipes-devtools/m4/m4/ac_config_links.patch
meta/recipes-devtools/mklibs/files/add-missing-data-files.patch
meta/recipes-extended/mktemp/files/disable-strip.patch
meta/recipes-devtools/m4/m4/fix_for_circular_dependency.patch
meta/recipes-devtools/m4/m4/remove-gets.patch
meta/recipes-devtools/apt/files/db_linking_fix.patch
meta/recipes-devtools/qemu/qemu/disable-grabs.patch
meta/recipes-devtools/qemu/files/Qemu-Arm-versatilepb-Add-memory-size-checking.patch
meta/recipes-extended/screen/screen-4.0.3/screen-4.0.2-CVE-2009-1215.patch
meta/recipes-multimedia/alsa/alsa-utils/alsa-utils-aplay-interrupt-signal-handling-fix.patch
meta/recipes-devtools/apt/files/no-curl-hack.patch
meta/recipes-extended/screen/screen-4.0.3/fix-parallel-make.patch
meta/recipes-devtools/qemu/qemu/wacom.patch
meta/recipes-multimedia/tremor/tremor-20120314/tremor-arm-thumb2.patch
meta/recipes-devtools/xmlto/xmlto-0.0.26/configure.in-drop-the-test-of-xmllint-and-xsltproc.patch
meta/recipes-devtools/apt/apt-0.9.9.4/rpathfix.patch
meta/recipes-devtools/apt/apt-0.9.9.4/nodoc.patch
#+END_SRC

** End file
#+BEGIN_SRC 
alsa-utils
apt-0.9.9.4
cracklib
flex
gawk-3.1.5
gawk-4.1.1
libdrm
lighttpd
m4
mklibs
mktemp
qemu
screen-4.0.3
tremor-20120314
xmlto-0.0.26
#+END_SRC

* Greek Letters

Starting with a list of Greek letters, create a cross-reference table showing all of the Greek alpha-beta. You'll likely need to use digraphs (:help digraphs). Note that while most digraphs can be entered with either character first, lowercase sigma has two digraphs -- s* AND *s! Good luck!
** Start file
#+BEGIN_SRC 
alpha
beta
gamma
delta
epsilon
zeta
eta
theta
iota
kappa
lambda
mu
nu
ksi
omicron
pi
rho
sigma
tau
upsilon
phї
chi
psi
omega
#+END_SRC

** End file
#+BEGIN_SRC 
Α α   alpha
Β β   beta
Γ γ   gamma
Δ δ   delta
Ε ε   epsilon
Ζ ζ   zeta
Η η   eta
Θ θ   theta
Ι ι   iota
Κ κ   kappa
Λ λ   lambda
Μ μ   mu
Ν ν   nu
Ξ ξ   ksi
Ο ο   omicron
Π π   pi
Ρ ρ   rho
Σ σς  sigma
Τ τ   tau
Υ υ   upsilon
Φ φ   phї
Χ χ   chi
Ψ ψ   psi
Ω ω   omega
#+END_SRC

* Maze path

Follow the given motions and mark your path with Xs. Attention: This maze is quite big (20x20), please set your terminal size to at least 82.
** Start file
#+BEGIN_SRC 
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa8   8aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
8               8   8                       8       8                   8       8
8   8aaaaaaa8   8   8   8aaa8   8aaaaaaa8   8   8   8aaa8   8   8aaa8   8aaa8   8
8   8       8   8       8       8       8       8           8       8           8
8   8aaa8   8   8aaaaaaa8   8aaa8   8   8aaaaaaa8   8aaaaaaaaaaa8   8   8aaaaaaa8
8       8   8   8                   8   8           8               8   8       8
8aaa8   8   8   8   8aaa8   8aaaaaaa8   8aaa8   8aaaaaaaaaaaaaaaaaaaaaaa8   8   8
8   8   8   8       8   8       8   8       8                               8   8
8   8   8   8aaaaaaa8   8aaa8   8   8aaa8   8aaaaaaaaaaa8   8aaaaaaaaaaaaaaa8   8
8       8       8       8           8       8               8               8   8
8   8aaaaaaa8   8   8aaaaaaa8   8aaa8   8aaa8   8aaaaaaaaaaaaaaaaaaaaaaa8   8   8
8   8       8   8   8               8   8   8   8               8       8       8
8   8   8   8   8   8aaaaaaaaaaaaaaa8   8   8   8   8aaaaaaa8   8   8   8aaaaaaa8
8   8   8   8           8   8       8   8   8   8           8       8           8
8   8   8   8aaaaaaa8   8   8   8   8   8   8   8aaaaaaaaaaaaaaa8   8aaaaaaa8   8
8   8   8                   8   8       8   8                       8           8
8   8aaaaaaaaaaa8   8   8aaa8   8aaaaaaa8   8aaaaaaa8   8aaaaaaaaaaa8   8aaaaaaa8
8               8   8       8   8                       8               8       8
8aaa8   8aaa8   8   8aaaaaaa8   8aaaaaaaaaaaaaaaaaaaaaaa8   8   8aaaaaaa8   8   8
8   8       8       8       8               8               8   8       8   8   8
8   8   8   8aaaaaaa8   8   8aaaaaaaaaaa8   8   8aaaaaaaaaaa8   8   8   8   8   8
8       8               8   8           8   8       8       8   8   8       8   8
8   8aaaaaaaaaaaaaaaaaaa8   8   8aaaaaaa8   8   8aaa8   8   8   8   8aaa8   8   8
8   8               8   8   8       8       8   8       8       8       8   8   8
8aaa8   8aaaaaaaaaaa8   8aaaaaaa8   8   8aaa8   8   8aaaaaaaaaaaaaaaaaaa8   8   8
8       8           8               8   8       8   8                       8   8
8   8   8   8aaa8   8aaa8   8aaa8   8   8   8aaa8   8   8aaaaaaaaaaaaaaaaaaa8   8
8   8   8       8           8       8   8   8       8       8       8       8   8
8   8   8aaa8   8aaaaaaaaaaaaaaa8   8   8   8   8   8aaa8   8   8aaa8   8   8   8
8   8           8       8           8   8   8   8       8       8       8   8   8
8   8aaaaaaaaaaaaaaa8   8aaa8   8aaa8   8   8aaaaaaa8   8aaaaaaa8   8aaa8   8   8
8       8       8       8       8   8   8   8           8               8   8   8
8   8aaa8   8   8   8aaa8   8aaa8   8   8   8   8aaaaaaa8   8aaaaaaaaaaa8   8   8
8   8       8   8           8       8   8   8               8       8           8
8   8   8aaa8   8aaa8   8aaa8   8aaa8   8aaaaaaaaaaaaaaaaaaa8   8   8   8aaaaaaa8
8       8       8       8   8       8                           8   8           8
8aaaaaaa8   8aaa8   8aaa8   8aaa8   8aaaaaaaaaaaaaaaaaaaaaaaaaaa8   8aaaaaaaaaaa8
8   8       8       8           8       8       8                   8           8
8   8   8aaa8   8   8   8aaa8   8aaa8   8   8   8   8aaa8   8aaaaaaa8   8aaa8   8
8       8       8       8               8   8       8                   8       8
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa8   8aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa

Your path:
1j8h2j4h2j8l2k4l4j4l2j4h6j4h2k4h6j12l4j4h12j24l2k4l4j16h2j4h2k4h3j

Your help (or not):
s/\v(\d)(\D+)/\=repeat(submatch(2),str2nr(submatch(1)))/g
s/./&rX/g
:s/\D/& /g
#+END_SRC

** End file
#+BEGIN_SRC 
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa8 X 8aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
8               8   8         XXXXXXXXX     8       8                   8       8
8   8aaaaaaa8   8   8   8aaa8 X 8aaaaaaa8   8   8   8aaa8   8   8aaa8   8aaa8   8
8   8       8   8       8 XXXXX 8 XXXXX 8       8           8       8           8
8   8aaa8   8   8aaaaaaa8 X 8aaa8 X 8 X 8aaaaaaa8   8aaaaaaaaaaa8   8   8aaaaaaa8
8       8   8   8         XXXXXXXXX 8 X 8           8               8   8       8
8aaa8   8   8   8   8aaa8   8aaaaaaa8 X 8aaa8   8aaaaaaaaaaaaaaaaaaaaaaa8   8   8
8   8   8   8       8   8       8   8 XXXXX 8                               8   8
8   8   8   8aaaaaaa8   8aaa8   8   8aaa8 X 8aaaaaaaaaaa8   8aaaaaaaaaaaaaaa8   8
8       8       8       8           8 XXXXX 8               8               8   8
8   8aaaaaaa8   8   8aaaaaaa8   8aaa8 X 8aaa8   8aaaaaaaaaaaaaaaaaaaaaaa8   8   8
8   8       8   8   8               8 X 8   8   8               8       8       8
8   8   8   8   8   8aaaaaaaaaaaaaaa8 X 8   8   8   8aaaaaaa8   8   8   8aaaaaaa8
8   8   8   8           8   8 XXXXX 8 X 8   8   8           8       8           8
8   8   8   8aaaaaaa8   8   8 X 8 X 8 X 8   8   8aaaaaaaaaaaaaaa8   8aaaaaaa8   8
8   8   8                   8 X 8 XXXXX 8   8                       8           8
8   8aaaaaaaaaaa8   8   8aaa8 X 8aaaaaaa8   8aaaaaaa8   8aaaaaaaaaaa8   8aaaaaaa8
8               8   8       8 X 8                       8               8       8
8aaa8   8aaa8   8   8aaaaaaa8 X 8aaaaaaaaaaaaaaaaaaaaaaa8   8   8aaaaaaa8   8   8
8   8       8       8       8 XXXXXXXXXXXXX 8               8   8       8   8   8
8   8   8   8aaaaaaa8   8   8aaaaaaaaaaa8 X 8   8aaaaaaaaaaa8   8   8   8   8   8
8       8               8   8           8 X 8       8       8   8   8       8   8
8   8aaaaaaaaaaaaaaaaaaa8   8   8aaaaaaa8 X 8   8aaa8   8   8   8   8aaa8   8   8
8   8               8   8   8       8 XXXXX 8   8       8       8       8   8   8
8aaa8   8aaaaaaaaaaa8   8aaaaaaa8   8 X 8aaa8   8   8aaaaaaaaaaaaaaaaaaa8   8   8
8       8           8               8 X 8       8   8                       8   8
8   8   8   8aaa8   8aaa8   8aaa8   8 X 8   8aaa8   8   8aaaaaaaaaaaaaaaaaaa8   8
8   8   8       8           8       8 X 8   8       8       8       8       8   8
8   8   8aaa8   8aaaaaaaaaaaaaaa8   8 X 8   8   8   8aaa8   8   8aaa8   8   8   8
8   8           8       8           8 X 8   8   8       8       8       8   8   8
8   8aaaaaaaaaaaaaaa8   8aaa8   8aaa8 X 8   8aaaaaaa8   8aaaaaaa8   8aaa8   8   8
8       8       8       8       8   8 X 8   8           8               8   8   8
8   8aaa8   8   8   8aaa8   8aaa8   8 X 8   8   8aaaaaaa8   8aaaaaaaaaaa8   8   8
8   8       8   8           8       8 X 8   8               8 XXXXX 8           8
8   8   8aaa8   8aaa8   8aaa8   8aaa8 X 8aaaaaaaaaaaaaaaaaaa8 X 8 X 8   8aaaaaaa8
8       8       8       8   8       8 XXXXXXXXXXXXXXXXXXXXXXXXX 8 X 8           8
8aaaaaaa8   8aaa8   8aaa8   8aaa8   8aaaaaaaaaaaaaaaaaaaaaaaaaaa8 X 8aaaaaaaaaaa8
8   8       8       8           8       8 XXXXX 8 XXXXXXXXXXXXXXXXX 8           8
8   8   8aaa8   8   8   8aaa8   8aaa8   8 X 8 X 8 X 8aaa8   8aaaaaaa8   8aaa8   8
8       8       8       8               8 X 8 XXXXX 8                   8       8
aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa8 X 8aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa

Your path:
1j8h2j4h2j8l2k4l4j4l2j4h6j4h2k4h6j12l4j4h12j24l2k4l4j16h2j4h2k4h3j

Your help (or not):
s/\v(\d)(\D+)/\=repeat(submatch(2),str2nr(submatch(1)))/g
s/./&rX/g
:s/\D/& /g
#+END_SRC

* Change The Perspective

This is a go game recodes file(.sgf file, refer to http://www.red-bean.com/sgf/). It base on such a coordinate system: in vertical direction, is from top(farthest end) to bottom, mark as a,b,c,...，s(19*19 board); in horizontal direction, is from left to right, uses the same notations. For Example, the coordinate notation 'cq', is the position at the bottom-left corner(vertical coordinate first). The record is from one player's perspective. We need to change to another's, but we don't want to change coordinate system, let it keep top to bottom and left to right. so we have to change the coordinates, a <-> s, b <-> r,c <-> q, etc. the Position 'cq', as transformation, it will be 'qd'.
** Start file
#+BEGIN_SRC 
(
;GM[1]SZ[19]
;B[dp];W[pq];B[dd];W[pd];B[qo];W[pl];B[no];W[mq];B[qf];W[nc];B[pi];W[qe]
;B[pf];W[nl];B[lo];W[kp];B[ll];W[ko];B[ln];W[pj];B[oj];W[oi];B[nj];W[qi]
;B[ph];W[qj];B[ni];W[qh];B[oh];W[cj];B[lc];W[rf];B[rg];W[re];B[qg];W[mk]
;B[kj];W[rh];B[gq];W[op];B[pn];W[fc];B[cg];W[ic];B[cl];W[bn];B[co];W[cq]
;B[bo];W[eq];B[ep];W[fq];B[fp];W[gr];B[gp];W[hr];B[ch];W[ej];B[ck];W[eh]
;B[bj];W[ee];B[ed];W[fd];B[fe];W[ef];B[ge];W[gg];B[ie];W[db];B[cd];W[hi]
;B[ke];W[cc];B[fk];W[ji];B[ig];W[fj];B[hh];W[ih];B[hg];W[gh];B[jh];W[ii]
;B[ki];W[hf];B[if];W[he];B[hd];W[gf];B[id];W[gd];B[hc];W[qp];B[sg];W[qm]
;B[ro];W[kh];B[pb];W[ob];B[pc];W[od];B[rc];W[rd];B[mb];W[qc];B[jg];W[dq]
;B[rq];W[ip];B[ok];W[ol];B[sh];W[mm];B[rp];W[kk];B[kn];W[lk];B[io];W[oo]
;B[on];W[nn];B[np];W[oq]
)
#+END_SRC

** End file
#+BEGIN_SRC 
(
;GM[1]SZ[19]
;B[pd];W[dc];B[pp];W[dp];B[ce];W[dh];B[fe];W[gc];B[cn];W[fq];B[dk];W[co]
;B[dn];W[fh];B[he];W[id];B[hh];W[ie];B[hf];W[dj];B[ej];W[ek];B[fj];W[ck]
;B[dl];W[cj];B[fk];W[cl];B[el];W[qj];B[hq];W[bn];B[bm];W[bo];B[cm];W[gi]
;B[ij];W[bl];B[mc];W[ed];B[df];W[nq];B[qm];W[kq];B[qh];W[rf];B[qe];W[qc]
;B[re];W[oc];B[od];W[nc];B[nd];W[mb];B[md];W[lb];B[ql];W[oj];B[qi];W[ol]
;B[rj];W[oo];B[op];W[np];B[no];W[on];B[mo];W[mm];B[ko];W[pr];B[qp];W[lk]
;B[io];W[qq];B[ni];W[jk];B[km];W[nj];B[ll];W[kl];B[lm];W[ml];B[jl];W[kk]
;B[ik];W[ln];B[kn];W[lo];B[lp];W[mn];B[kp];W[mp];B[lq];W[cd];B[am];W[cg]
;B[be];W[il];B[dr];W[er];B[dq];W[ep];B[bq];W[bp];B[gr];W[cq];B[jm];W[pc]
;B[bc];W[kd];B[ei];W[eh];B[al];W[gg];B[bd];W[ii];B[if];W[hi];B[ke];W[ee]
;B[ef];W[ff];B[fd];W[ec]
)
#+END_SRC

* Refactor to Helpers

This Rails partial is almost all template escapes. Put it into a helper, and refactor each case to methods so we can build out the controls for each. (I've converted to tabs - fighting with Vimgolf's default config shouldn't be part of the challenge.)
** Start file
#+BEGIN_SRC 
## _controls.html.erb
<div class='controls'>
        <% if event.author == current_user -%>
                <%= link_to "Edit Activity", edit_event_path(event), :class => 'button' %>
        <% else -%>
                <% if current_user.attending? event -%>
                        <%= link_to "Leave", leave_event_path(event), :class => "button neg", :method => :post %>
                <% else -%>
                        <% if current_user.invited_to? event -%>
                                <%= link_to "Accept Invite", join_event_path(event), :class => "button pos", :method => :post %>
                        <% else -%>
                                <%= link_to "I'm Going", join_event_path(event), :class => "button pos", :method => :post %>
                        <% end -%>
                <% end -%>
        <% end -%>
</div>

## event_helper.rb
module EventHelper
end
#+END_SRC

** End file
#+BEGIN_SRC 
## _controls.html.erb
<div class='controls'>
        <%= event_controls event %>
</div>

## event_helper.rb
module EventHelper
        def event_controls(event)
                if event.author == current_user
                        author_controls(event)
                elsif current_user.attending? event
                        attendee_controls(event)
                elsif current_user.invited_to? event
                        invitee_controls(event)
                else
                        public_controls(event)
                end
        end

        def author_controls(event)
                link_to "Edit Activity", edit_event_path(event), :class => 'button'
        end

        def attendee_controls(event)
                link_to "Leave", leave_event_path(event), :class => "button neg", :method => :post
        end

        def invitee_controls(event)
                link_to "Accept Invite", join_event_path(event), :class => "button pos", :method => :post
        end

        def public_controls(event)
                link_to "I'm Going", join_event_path(event), :class => "button pos", :method => :post
        end
end
#+END_SRC

* My cafe needs a new menu

Help! My cafe needs a new menu and I've only got this plain-text file from the kitchen. In order to get it printed, I need to transform it into a markdown file with; headings for each type of item, prices on each menu item, dietary options and a key down the bottom.
** Start file
#+BEGIN_SRC 
mocha drink 4
tea drink 3
iced-tea drink 5
iced-mocha drink 5
eggs-on-toast breakfast gluten-free-option,vegetarian 14
bacon-and-eggs breakfast 16
vegan-deluxe breakfast gluten-free-option,vegetarian 14
meaty-deluxe breakfast 20
big-burger lunch gluten-free-option,vegetarian-option 14
steak-and-chips lunch 22
#+END_SRC

** End file
#+BEGIN_SRC 
# Drink
- Mocha - $4
- Tea - $3
- Iced Tea - $5
- Iced Mocha - $5

# Breakfast
- Eggs On Toast (GFO,V) - $14
- Bacon And Eggs - $16
- Vegan Deluxe (GFO,V) - $14
- Meaty Deluxe - $20

# Lunch
- Big Burger (GFO,VO) - $14
- Steak And Chips - $22

> *GFO = Gluten Free Option, V = Vegetarian, VO = Vegetarian Option
#+END_SRC

* Palindrome numbers

For each number compute its associated palindrome. First number (first line) has been eaten! #prime
** Start file
#+BEGIN_SRC 
??
211
2111
10111
12011
20021
21101
#+END_SRC

** End file
#+BEGIN_SRC 
121
23632
2347432
112242211
132373231
240292042
213373312
#+END_SRC

* 50 factorials mod 97

List 1! to 50!, but give your answer mod 97.
** Start file
#+BEGIN_SRC 
Factorials
#+END_SRC

** End file
#+BEGIN_SRC 
1
2
6
24
23
41
93
65
3
30
39
80
70
10
53
72
60
13
53
90
47
64
17
20
15
2
54
57
4
23
34
21
14
88
73
9
42
44
67
61
76
88
1
44
40
94
53
22
11
65
#+END_SRC

* Config Sections

Section me!
** Start file
#+BEGIN_SRC 
SECTION1
SECTION TWO
SECTION THREE
THIS IS ANOTHER SECTION
#+END_SRC

** End file
#+BEGIN_SRC 
##############################
##         SECTION1         ##
##############################

##############################
##       SECTION TWO        ##
##############################

##############################
##      SECTION THREE       ##
##############################

##############################
## THIS IS ANOTHER SECTION  ##
##############################
#+END_SRC

* 199 Fibonacci Numbers

Generate 199 Fibonacci Numbers using, if you like, the function S(x,y), a vimscript to sum two big numbers in reverse order.
** Start file
#+BEGIN_SRC 
"S - function to sum two big numbers in reverse order
fu! S(x,y)
let t=0
let s=''
let na=strlen(a:x)
let nb=strlen(a:y)
if na<nb
let m=nb
let a=a:x . repeat('0',m - na)
let b=a:y
else
let m=na
let b=a:y . repeat('0',m - nb)
let a=a:x
en
for i in range(0,m-1)
let c=a[i]+b[i]+t
let s.=c%10
let t=c/10
endfo
if t>0
let s.=t
en
retu s
endf

1
2
#+END_SRC

** End file
#+BEGIN_SRC 
                                         1
                                         2
                                         3
                                         5
                                         8
                                        13
                                        21
                                        34
                                        55
                                        89
                                       144
                                       233
                                       377
                                       610
                                       987
                                      1597
                                      2584
                                      4181
                                      6765
                                     10946
                                     17711
                                     28657
                                     46368
                                     75025
                                    121393
                                    196418
                                    317811
                                    514229
                                    832040
                                   1346269
                                   2178309
                                   3524578
                                   5702887
                                   9227465
                                  14930352
                                  24157817
                                  39088169
                                  63245986
                                 102334155
                                 165580141
                                 267914296
                                 433494437
                                 701408733
                                1134903170
                                1836311903
                                2971215073
                                4807526976
                                7778742049
                               12586269025
                               20365011074
                               32951280099
                               53316291173
                               86267571272
                              139583862445
                              225851433717
                              365435296162
                              591286729879
                              956722026041
                             1548008755920
                             2504730781961
                             4052739537881
                             6557470319842
                            10610209857723
                            17167680177565
                            27777890035288
                            44945570212853
                            72723460248141
                           117669030460994
                           190392490709135
                           308061521170129
                           498454011879264
                           806515533049393
                          1304969544928657
                          2111485077978050
                          3416454622906707
                          5527939700884757
                          8944394323791464
                         14472334024676221
                         23416728348467685
                         37889062373143906
                         61305790721611591
                         99194853094755497
                        160500643816367088
                        259695496911122585
                        420196140727489673
                        679891637638612258
                       1100087778366101931
                       1779979416004714189
                       2880067194370816120
                       4660046610375530309
                       7540113804746346429
                      12200160415121876738
                      19740274219868223167
                      31940434634990099905
                      51680708854858323072
                      83621143489848422977
                     135301852344706746049
                     218922995834555169026
                     354224848179261915075
                     573147844013817084101
                     927372692193078999176
                    1500520536206896083277
                    2427893228399975082453
                    3928413764606871165730
                    6356306993006846248183
                   10284720757613717413913
                   16641027750620563662096
                   26925748508234281076009
                   43566776258854844738105
                   70492524767089125814114
                  114059301025943970552219
                  184551825793033096366333
                  298611126818977066918552
                  483162952612010163284885
                  781774079430987230203437
                 1264937032042997393488322
                 2046711111473984623691759
                 3311648143516982017180081
                 5358359254990966640871840
                 8670007398507948658051921
                14028366653498915298923761
                22698374052006863956975682
                36726740705505779255899443
                59425114757512643212875125
                96151855463018422468774568
               155576970220531065681649693
               251728825683549488150424261
               407305795904080553832073954
               659034621587630041982498215
              1066340417491710595814572169
              1725375039079340637797070384
              2791715456571051233611642553
              4517090495650391871408712937
              7308805952221443105020355490
             11825896447871834976429068427
             19134702400093278081449423917
             30960598847965113057878492344
             50095301248058391139327916261
             81055900096023504197206408605
            131151201344081895336534324866
            212207101440105399533740733471
            343358302784187294870275058337
            555565404224292694404015791808
            898923707008479989274290850145
           1454489111232772683678306641953
           2353412818241252672952597492098
           3807901929474025356630904134051
           6161314747715278029583501626149
           9969216677189303386214405760200
          16130531424904581415797907386349
          26099748102093884802012313146549
          42230279526998466217810220532898
          68330027629092351019822533679447
         110560307156090817237632754212345
         178890334785183168257455287891792
         289450641941273985495088042104137
         468340976726457153752543329995929
         757791618667731139247631372100066
        1226132595394188293000174702095995
        1983924214061919432247806074196061
        3210056809456107725247980776292056
        5193981023518027157495786850488117
        8404037832974134882743767626780173
       13598018856492162040239554477268290
       22002056689466296922983322104048463
       35600075545958458963222876581316753
       57602132235424755886206198685365216
       93202207781383214849429075266681969
      150804340016807970735635273952047185
      244006547798191185585064349218729154
      394810887814999156320699623170776339
      638817435613190341905763972389505493
     1033628323428189498226463595560281832
     1672445759041379840132227567949787325
     2706074082469569338358691163510069157
     4378519841510949178490918731459856482
     7084593923980518516849609894969925639
    11463113765491467695340528626429782121
    18547707689471986212190138521399707760
    30010821454963453907530667147829489881
    48558529144435440119720805669229197641
    78569350599398894027251472817058687522
   127127879743834334146972278486287885163
   205697230343233228174223751303346572685
   332825110087067562321196029789634457848
   538522340430300790495419781092981030533
   871347450517368352816615810882615488381
  1409869790947669143312035591975596518914
  2281217241465037496128651402858212007295
  3691087032412706639440686994833808526209
  5972304273877744135569338397692020533504
  9663391306290450775010025392525829059713
 15635695580168194910579363790217849593217
 25299086886458645685589389182743678652930
 40934782466626840596168752972961528246147
 66233869353085486281758142155705206899077
107168651819712326877926895128666735145224
173402521172797813159685037284371942044301
280571172992510140037611932413038677189525
#+END_SRC

* LaTeX to XML Math Delimiters

Vim is amazing when used to edit MediaWiki text, but typing "<math> . . . </math>" can be tiresome and frustrating if formulas are used often. LaTeX delimiters are so concise and even come in two flavors: "\( . . . \)" for inline math and "\[ . . . \]" for centered formulas. The goal is to perform the following conversions: "\( . . . \)" becomes "<math>. . .</math>" "\[ . . . \]" becomes "<center><math>. . .</math></center>"
** Start file
#+BEGIN_SRC 
Given two vectors \(\vec{x}\) and \(\vec{y}\) in \( \mathbb{R}^n \),
their '''dot product''' or '''inner product''' is defined as the following:

\[ \sum_{i=0}^{n} x_i \, y_i \]

----

Integration by parts is another way of writing the product rule of differentiation.
For two functions \(f(x)\) and \(g(x)\), the following are equivalent:

\[ \begin{align}
\frac{\mathrm{d}}{\mathrm{d}x} \left( f(x) \, g(x) \right) &= f'(x) \, g(x) + f(x) \, g'(x) \\
\int f(x) \, g'(x) \, \mathrm{d}x &= f(x) \, g(x) - \int f'(x) \, g(x) \, \mathrm{d}x
\end{align} \]

----

Matrix multiplication is not commutative

\(
\begin{align}
\begin{bmatrix}
    a_{11} & a_{12} \\
    a_{21} & a_{22}
\end{bmatrix} \,
\begin{bmatrix}
    b_{11} & b_{12} \\
    b_{21} & b_{22}
\end{bmatrix} &\ne
\begin{bmatrix}
    b_{11} & b_{12} \\
    b_{21} & b_{22}
\end{bmatrix} \,
\begin{bmatrix}
    a_{11} & a_{12} \\
    a_{21} & a_{22}
\end{bmatrix} \\

\begin{bmatrix}
    a_{11} \, b_{11} + a_{12} \, b_{21} & a_{11} \, b_{12} + a_{12} \, b_{22} \\
    a_{21} \, b_{11} + a_{22} \, b_{21} & a_{21} \, b_{12} + a_{22} \, b_{22}
\end{bmatrix} &\ne
\begin{bmatrix}
    a_{11} \, b_{11} + a_{21} \, b_{12} & a_{12} \, b_{11} + a_{22} \, b_{12} \\
    a_{11} \, b_{21} + a_{21} \, b_{22} & a_{12} \, b_{21} + a_{22} \, b_{22}
\end{bmatrix}
\begin{align}
\)

''Quod erat demonstrandum''.
#+END_SRC

** End file
#+BEGIN_SRC 
Given two vectors <math>\vec{x}</math> and <math>\vec{y}</math> in <math>\mathbb{R}^n</math>,
their '''dot product''' or '''inner product''' is defined as the following:

<center><math>\sum_{i=0}^{n} x_i \, y_i</math></center>

----

Integration by parts is another way of writing the product rule of differentiation.
For two functions <math>f(x)</math> and <math>g(x)</math>, the following are equivalent:

<center><math>\begin{align}
\frac{\mathrm{d}}{\mathrm{d}x} \left( f(x) \, g(x) \right) &= f'(x) \, g(x) + f(x) \, g'(x) \\
\int f(x) \, g'(x) \, \mathrm{d}x &= f(x) \, g(x) - \int f'(x) \, g(x) \, \mathrm{d}x
\end{align}</math></center>

----

Matrix multiplication is not commutative

<math>
\begin{align}
\begin{bmatrix}
    a_{11} & a_{12} \\
    a_{21} & a_{22}
\end{bmatrix} \,
\begin{bmatrix}
    b_{11} & b_{12} \\
    b_{21} & b_{22}
\end{bmatrix} &\ne
\begin{bmatrix}
    b_{11} & b_{12} \\
    b_{21} & b_{22}
\end{bmatrix} \,
\begin{bmatrix}
    a_{11} & a_{12} \\
    a_{21} & a_{22}
\end{bmatrix} \\

\begin{bmatrix}
    a_{11} \, b_{11} + a_{12} \, b_{21} & a_{11} \, b_{12} + a_{12} \, b_{22} \\
    a_{21} \, b_{11} + a_{22} \, b_{21} & a_{21} \, b_{12} + a_{22} \, b_{22}
\end{bmatrix} &\ne
\begin{bmatrix}
    a_{11} \, b_{11} + a_{21} \, b_{12} & a_{12} \, b_{11} + a_{22} \, b_{12} \\
    a_{11} \, b_{21} + a_{21} \, b_{22} & a_{12} \, b_{21} + a_{22} \, b_{22}
\end{bmatrix}
\begin{align}
</math>

''Quod erat demonstrandum''.
#+END_SRC

* Custom McCarthy sequence

Generate the first one hundred and twenty numbers (starting with n=1). See here for some inspiration: http://en.wikipedia.org/wiki/McCarthy_91_function
** Start file
#+BEGIN_SRC 
" Humm... :so%

" Custom McCarthy 91 function
" M(n) = { n          if n > 97
"        { M(M(n+1))  if n <= 97
function! Mc98(n)
  if a:n > 97
    return a:n
  else
    return Mc98(Mc98(a:n + 1))
  endif
endfunction

function! Mc98Line()
  let l = getline('.')
  call setline('.', Mc98(l))
endfunction

" Humm...
"command! -range Mc98Cmd <line1>,<line2>call Mc98Line()
nmap M ciw<C-R>=Mc98(<C-R>")<CR><Esc>
"0put=range(1,120)
#+END_SRC

** End file
#+BEGIN_SRC 
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
98
99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
#+END_SRC

* Hail to Alekseï Pajitnov

Wanna play tetris? Don't panic, it's quite long but there's no piece rotation. Little advice: source the file, Luke!
** Start file
#+BEGIN_SRC 
  ||          ||   Score
  ||          ||   -----
  ||   NN     ||     n/a
  ||    NN    ||
  ||          ||   Level
  ||          ||   -----
  ||          ||       1
  ||          ||
  ||          ||   Lines
  ||          ||   -----
  ||          ||       0
  ||          ||
  ||          ||
  ||          ||
  ||          ||
  ||          ||
  ==============

# Your pieces:
let @a='rAj.j.l.2kh'
let @b='rBl.j.j.2kh'
let @m='rMj.l.j.2kh'
let @n='rNl.j.l.k2h'
let @o='ROOhj.kh'
let @t='rTj.h.2l.kh'
let @w='rWj.j.j.3k'
#+END_SRC

** End file
#+BEGIN_SRC 
  ||          ||   Score
  ||          ||   -----
  ||          ||     n/a
  ||      W   ||
  ||      W   ||   Level
  ||      W   ||   -----
  ||      W   ||       1
  ||          ||
  ||          ||   Lines
  ||          ||   -----
  ||          ||       7
  ||          ||
  || OO  M BB ||
  ||AOOOOMMAB ||
  ||ANNOOTMAB ||
  ||AANNTTTAA ||
  ==============

# Your pieces:
let @a='rAj.j.l.2kh'
let @b='rBl.j.j.2kh'
let @m='rMj.l.j.2kh'
let @n='rNl.j.l.k2h'
let @o='ROOhj.kh'
let @t='rTj.h.2l.kh'
let @w='rWj.j.j.3k'
#+END_SRC

* Acute accents

Featuring all 17 lowercase letters with an acute accent digraph. Find a way to automate the digraphs.
** Start file
#+BEGIN_SRC 
acegiklmnoprsuwyz
#+END_SRC

** End file
#+BEGIN_SRC 
áćéǵíḱĺḿńóṕŕśúẃýź
#+END_SRC

* Convert pasted text into Markdown

I often need to copy/paste text into Markdown files. The challenge here is to wrap the lines in a way that prefers breaks after periods, commas, or other logical demarcations. There should be no spaces at the beginning of a line.
** Start file
#+BEGIN_SRC 
Four score and seven years ago our fathers brought forth on this continent, a new nation, conceived in Liberty, and dedicated to the proposition that all men are created equal.
Now we are engaged in a great civil war, testing whether that nation, or any nation so conceived and so dedicated, can long endure. We are met on a great battle-field of that war. We have come to dedicate a portion of that field, as a final resting place for those who here gave their lives that that nation might live. It is altogether fitting and proper that we should do this.
But, in a larger sense, we can not dedicate -- we can not consecrate -- we can not hallow -- this ground. The brave men, living and dead, who struggled here, have consecrated it, far above our poor power to add or detract. The world will little note, nor long remember what we say here, but it can never forget what they did here. It is for us the living, rather, to be dedicated here to the unfinished work which they who fought here have thus far so nobly advanced. It is rather for us to be here dedicated to the great task remaining before us -- that from these honored dead we take increased devotion to that cause for which they gave the last full measure of devotion -- that we here highly resolve that these dead shall not have died in vain -- that this nation, under God, shall have a new birth of freedom -- and that government of the people, by the people, for the people, shall not perish from the earth.
Abraham Lincoln
November 19, 1863
#+END_SRC

** End file
#+BEGIN_SRC 
Four score and seven years ago our fathers brought forth
on this continent, a new nation, conceived in Liberty,
and dedicated to the proposition that all men are created equal.

Now we are engaged in a great civil war, testing whether that
nation, or any nation so conceived and so dedicated, can long endure.
We are met on a great battle-field of that war.
We have come to dedicate a portion of that field, as a final resting
place for those who here gave their lives that that nation might live.
It is altogether fitting and proper that we should do this.

But, in a larger sense, we can not dedicate -- we can not consecrate --
we can not hallow -- this ground.
The brave men, living and dead, who struggled here, have consecrated it,
far above our poor power to add or detract.
The world will little note, nor long remember what we say here,
but it can never forget what they did here.
It is for us the living, rather, to be dedicated here to the
unfinished work which they who fought here have thus far so nobly advanced.
It is rather for us to be here dedicated to the great task
remaining before us -- that from these honored dead we take increased
devotion to that cause for which they gave the last full measure of
devotion -- that we here highly resolve that these dead shall not
have died in vain -- that this nation, under God, shall have a new
birth of freedom -- and that government of the people, by the people,
for the people, shall not perish from the earth.

Abraham Lincoln
November 19, 1863
#+END_SRC

* Forgot to follow the naming convention...

Rename everything like MY_VAR_SOMETHING to MyVarSomething.
** Start file
#+BEGIN_SRC 
int WaterAdder::OnTimer(Universe u)
{
  const int MY_VAR_TYPE_ID = Universe::TYPE_ID_PLANETARY_SYSTEM;
  Universe::Object MY_VAR_SUN_TEMPLATE;
  this->InitializeTheSun(MY_VAR_SUN_TEMPLATE);

  // auto & MY_VAR_BRIGHT_STAR = ptheir_->StarClass("G2V");
  // Fails after some time passes in u:
  // Assert(Universe::IsElement(MY_VAR_SUN_TEMPLATE, MY_VAR_BRIGHT_STAR));

  // Just to doublecheck.
  Assert(MY_VARIANT(ptheir_->OTHER_GUYS_VAR).IsEqual(MY_VAR_SUN_TEMPLATE));

  // TODO: initialize MY_VAR_EARTH_TEMPLATE

  Universe::TYPE_ID_INFO<MY_VAR_TYPE_ID>::Type MY_VAR_SOLAR_SYSTEM_TEMPLATE();
  MY_VAR_SOLAR_SYSTEM_TEMPLATE.Add({MY_VAR_SUN_TEMPLATE,
    ptheir_->THEIR_VAR_MERCURY, ptheir_->THEIR_VAR_VENUS,
    MY_VAR_EARTH_TEMPLATE});

  Universe::TYPE_ID_INFO<MY_VAR_TYPE_ID>::Type *MY_VAR_SOLAR_SYSTEM =
    u.SearchByTemplate<MY_VAR_TYPE_ID>(MY_VAR_SOLAR_SYSTEM_TEMPLATE);
  Assert(MY_VARIABLE_CHECK(MY_VAR_SOLAR_SYSTEM));
  
  auto & MY_VAR_SUN = MY_VAR_SOLAR_SYSTEM->GetStar(0);
  auto MY_VAR_MASS = MY_VAR_SUN.GetMass();
  auto MY_VAR_DIST = Universe::Quantity::Meters(MY_VAR_MASS.InKg() * 1e-20);
  Universe::Quantity::VELOCITY_T::Type v;
  Assert(GeneralRelativity::GetOrbitalVelocity(u, MY_VAR_MASS,
    MY_VAR_DIST, &v));
  auto MY_VAR_VELOCITY = vector4<Universe::Quantity::TYPE_SPEED::Type>::From3(
    GeneralRelativity::c, rnd.UnitVector3() * v);
  vector3 MY_VAR_POSITION = GeneralRelativity::RegularizedShift(u, 
    MY_VAR_SUN.GetPos(), rnd.UnitVector3(), MY_VAR_DIST);
  auto MY_VAR_WATER_MASS = std::max( MY_VAR_MASS * 4e-17,
    Universe::Quantity::Kg(63311*1.0e9));

  // Let the fun begin.
  WaterAdder::AddWater(u, MY_VAR_WATER_MASS, MY_VAR_POSITION, MY_VAR_VELOCITY);

  WaterAdder::SetTimer(Universe::Quantity::Second());
}
// TODO: Don't use long variable names like
// MY_VAR_SOLAR_SYSTEM_TEMPLATE_CHECKER_FOR_WATER_ADDER
#+END_SRC

** End file
#+BEGIN_SRC 
int WaterAdder::OnTimer(Universe u)
{
  const int MyVarTypeId = Universe::TYPE_ID_PLANETARY_SYSTEM;
  Universe::Object MyVarSunTemplate;
  this->InitializeTheSun(MyVarSunTemplate);

  // auto & MyVarBrightStar = ptheir_->StarClass("G2V");
  // Fails after some time passes in u:
  // Assert(Universe::IsElement(MyVarSunTemplate, MyVarBrightStar));

  // Just to doublecheck.
  Assert(MY_VARIANT(ptheir_->OTHER_GUYS_VAR).IsEqual(MyVarSunTemplate));

  // TODO: initialize MyVarEarthTemplate

  Universe::TYPE_ID_INFO<MyVarTypeId>::Type MyVarSolarSystemTemplate();
  MyVarSolarSystemTemplate.Add({MyVarSunTemplate,
    ptheir_->THEIR_VAR_MERCURY, ptheir_->THEIR_VAR_VENUS,
    MyVarEarthTemplate});

  Universe::TYPE_ID_INFO<MyVarTypeId>::Type *MyVarSolarSystem =
    u.SearchByTemplate<MyVarTypeId>(MyVarSolarSystemTemplate);
  Assert(MY_VARIABLE_CHECK(MyVarSolarSystem));
  
  auto & MyVarSun = MyVarSolarSystem->GetStar(0);
  auto MyVarMass = MyVarSun.GetMass();
  auto MyVarDist = Universe::Quantity::Meters(MyVarMass.InKg() * 1e-20);
  Universe::Quantity::VELOCITY_T::Type v;
  Assert(GeneralRelativity::GetOrbitalVelocity(u, MyVarMass,
    MyVarDist, &v));
  auto MyVarVelocity = vector4<Universe::Quantity::TYPE_SPEED::Type>::From3(
    GeneralRelativity::c, rnd.UnitVector3() * v);
  vector3 MyVarPosition = GeneralRelativity::RegularizedShift(u, 
    MyVarSun.GetPos(), rnd.UnitVector3(), MyVarDist);
  auto MyVarWaterMass = std::max( MyVarMass * 4e-17,
    Universe::Quantity::Kg(63311*1.0e9));

  // Let the fun begin.
  WaterAdder::AddWater(u, MyVarWaterMass, MyVarPosition, MyVarVelocity);

  WaterAdder::SetTimer(Universe::Quantity::Second());
}
// TODO: Don't use long variable names like
// MyVarSolarSystemTemplateCheckerForWaterAdder
#+END_SRC

* No naked if allowed!

House style forbids naked condition statements, comments should start with a space character and be on their own line. Good luck!
** Start file
#+BEGIN_SRC
#include <sock.h>
if (recvfrom(s, (char*)&ms, sizeof(ms), 0, foo, bar) >= 0) //receive initial message frame
{
        f++;
        if (f == snwseq) //if its the right sequence
        {
                if (sendto(s, (char*)&a, sizeof(a), 0, foo, bar) > 0) //Send ACK
                        log << "Send ACK " << snwseq << ".\n";
                else
                        cout << "Error!" << endl;
        }
        else //wrong sequence
        {
                receive_packet_transfer(s, a, sa, f, slen, snwseq, num); //wait for correct packet
        }
}
else
        cout << "Error!" << endl;
#+END_SRC

** End file
#+BEGIN_SRC
#include <sock.h>
if (recvfrom(s, (char*)&ms, sizeof(ms), 0, foo, bar) >= 0) {
        // receive initial message frame
        f++;
        if (f == snwseq) {
                // if its the right sequence
                if (sendto(s, (char*)&a, sizeof(a), 0, foo, bar) > 0) {
                        // Send ACK
                        log << "Send ACK " << snwseq << ".\n";
                } else {
                        cout << "Error!" << endl;
                }
        } else {
                // wrong sequence
                receive_packet_transfer(s, a, sa, f, slen, snwseq, num);
        }
} else {
        cout << "Error!" << endl;
}
#+END_SRC

* Conway sequence

Generate the the first fifteen numbers. See here for more information: http://en.wikipedia.org/wiki/Look-and-say_sequence
** Start file
#+BEGIN_SRC 
submatch(
#+END_SRC

** End file
#+BEGIN_SRC 
1
11
21
1211
111221
312211
13112221
1113213211
31131211131221
13211311123113112211
11131221133112132113212221
3113112221232112111312211312113211
1321132132111213122112311311222113111221131221
11131221131211131231121113112221121321132132211331222113112211
311311222113111231131112132112311321322112111312211312111322212311322113212221
#+END_SRC

* Splits long lines in more readable ones

Those tests have too long lines. We have to split the to have more readable ones. This is based on a real project with Ruby and RSpec.
** Start file
#+BEGIN_SRC

require 'spec_helper'

describe ContentsController, type: :controller do
  before :each do
    set_request_on_domain :domain_test
    sign_in users(:admin)
  end

  describe '#update_categories' do
    let(:content) { contents(:adsl_cancel_question).set(intervention: nil) }

    it 'is success' do
      put :update_categories, id: content.id, category_ids: [categories(:mobile).id, categories(:technical).id], thread_id: content_threads(:adsl_cancel).id
      expect(response).to be_success
      expect(response.body).to be_blank
    end

    it 'is success if mandatory categories are not specified' do
      expect {
        put :update_categories, id: content.id, category_ids: [], thread_id: content_threads(:adsl_cancel).id
      }.to_not change { content }
      expect(response).to be_success
    end

    it 'updates categories' do
      expect {
        put :update_categories, id: content.id, category_ids: [categories(:mobile).id, categories(:technical).id], thread_id: content_threads(:adsl_cancel).id
      }.to change { content.reload.categories.to_a.sort }.from(array_including([categories(:internet), categories(:sales)])).to(array_including([categories(:technical), categories(:mobile)]))
    end

    it 'sets categories' do
      expect {
        put :update_categories, id: contents(:new_smartphone).id, category_ids: [categories(:mobile).id, categories(:technical).id], thread_id: content_threads(:new_smartphone).id
      }.to change { contents(:new_smartphone).reload.categories.to_a.sort }.from([]).to([categories(:technical), categories(:mobile)])
    end
  end
end
#+END_SRC

** End file
#+BEGIN_SRC
require 'spec_helper'

describe ContentsController, type: :controller do
  before :each do
    set_request_on_domain :domain_test
    sign_in users(:admin)
  end

  describe '#update_categories' do
    let(:content) { contents(:adsl_cancel_question).set(intervention: nil) }

    it 'is success' do
      put :update_categories,
        id: content.id,
        category_ids: [categories(:mobile).id, categories(:technical).id],
        thread_id: content_threads(:adsl_cancel).id
      expect(response).to be_success
      expect(response.body).to be_blank
    end

    it 'is success if mandatory categories are not specified' do
      expect {
        put :update_categories,
          id: content.id,
          category_ids: [],
          thread_id: content_threads(:adsl_cancel).id
      }.to_not change { content }
      expect(response).to be_success
    end

    it 'updates categories' do
      expect {
        put :update_categories,
          id: content.id,
          category_ids: [categories(:mobile).id, categories(:technical).id],
          thread_id: content_threads(:adsl_cancel).id
      }.to change { content.reload.categories.to_a.sort }
        .from(array_including([categories(:internet), categories(:sales)]))
        .to(array_including([categories(:technical), categories(:mobile)]))
    end

    it 'sets categories' do
      expect {
        put :update_categories,
          id: contents(:new_smartphone).id,
          category_ids: [categories(:mobile).id, categories(:technical).id],
          thread_id: content_threads(:new_smartphone).id
      }.to change { contents(:new_smartphone).reload.categories.to_a.sort }
        .from([])
        .to([categories(:technical), categories(:mobile)])
    end
  end
end
#+END_SRC

* Turn the x

Turn the x to a +

#+BEGIN_SRC
\     /
 \   /
  \ /
   X
  / \
 /   \
/     \
#+END_SRC

#+BEGIN_SRC

   |
   |
   |
---+---
   |
   |
   |
#+END_SRC

* Rural Post

Simple challenge to remove all but the post code on each line

#+BEGIN_SRC
RD 5 Gore 9775
RD 6 Gore 9776
RD 7 Gore 9777
RD 1 Great Barrier Island 0991
RD 1 Greta Valley 7387
RD 1 Greytown 5794
RD 1 Hamilton 3281
RD 2 Hamilton 3282
#+END_SRC

#+BEGIN_SRC
9775
9776
9777
0991
7387
5794
3281
3282
#+END_SRC

* Satisfy the go linter

You just came up with this briliant go vars package. But dang, you forgot to add comments to the exported variables. Can you add a comment over each variable with a TODO-placeholder?
Start file

#+BEGIN_SRC
package vars

var (
        Version string
        Debug bool
)
#+END_SRC

#+BEGIN_SRC
package vars

var (
        // Version TODO
        Version string
        // Debug TODO
        Debug bool
)
#+END_SRC

* prepend * to every non-blank line

Prepend an asterisk to every non-blank line in the input file.

#+BEGIN_SRC
This is a
very short

file, but it is 
still
full

of

surpises.
#+END_SRC

#+BEGIN_SRC
*This is a
*very short

*file, but it is 
*still
*full

*of

*surpises.
  
#+END_SRC

* Add semicolons

Simply add a semicolon at the end of each line

#+BEGIN_SRC
 super.onCreate(savedInstanceState)
 setContentView(R.layout.activity_second)
 Intent intent = getIntent()
 String text = intent.getStringExtra("text")

 TextView view = findViewById(R.id.textView2)
 view.setText(text)  
#+END_SRC

#+BEGIN_SRC
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_second);
 Intent intent = getIntent();
 String text = intent.getStringExtra("text");

 TextView view = findViewById(R.id.textView2);
 view.setText(text);
#+END_SRC

* Yo To Hello

Simply Turn Yo To 

** Start file
#+BEGIN_SRC
YO WORLD  
#+END_SRC

** End file

#+BEGIN_SRC
HELLO WORLD  
#+END_SRC
 
* xrandr outputs and dashes

uh oh, different video drivers identify display outputs with more dashes. Quick, need to change this xrandr script!
** Start file

#+BEGIN_SRC
xrandr \
  --output VIRTUAL1 --off \
  --output DP3 --off \
  --output eDP1 --off \
  --output DP1 --off \
  --output DP2 --off \
  --output HDMI3 --off \
  --output HDMI2 --off \
  --output HDMI1 --off \
  --output DP3-1 --off \
  --output DP3-3 --off \
  --output DP3-2 --off \
  --output eDP1 --primary --mode 1920x1080
#+END_SRC


** End file

#+BEGIN_SRC
xrandr \
  --output VIRTUAL-1 --off \
  --output DP-3 --off \
  --output eDP-1 --off \
  --output DP-1 --off \
  --output DP-2 --off \
  --output HDMI-3 --off \
  --output HDMI-2 --off \
  --output HDMI-1 --off \
  --output DP-3-1 --off \
  --output DP-3-3 --off \
  --output DP-3-2 --off \
  --output eDP-1 --primary --mode 1920x1080
#+END_SRC

* Multiline to Single Line

Convert a multiline, indented file to a single line with no whitespace
** Start file

#+BEGIN_SRC
api(
    'com.vimgolf.challenge'
)
#+END_SRC

** End file

#+BEGIN_SRC
api('com.vimgolf.challenge')
#+END_SRC

* Format the CSS

You just copied some CSS color names from the web and need to add them to your python module. Create the COLORS variable and assign a dict() with the names as keys and hex-colors as values. BEWARE OF THE TABS!!
** Start file

#+BEGIN_SRC
# https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
black   #000000
silver  #c0c0c0
gray    #808080
white   #ffffff
maroon  #800000
red     #ff0000
purple  #800080
fuchsia #ff00ff
green   #008000
lime    #00ff00
olive   #808000
yellow  #ffff00
navy    #000080
blue    #0000ff
teal    #008080
aqua    #00ffff
orange  #ffa500
aliceblue       #f0f8ff
antiquewhite    #faebd7
aquamarine      #7fffd4
azure   #f0ffff
beige   #f5f5dc
bisque  #ffe4c4
blanchedalmond  #ffebcd
blueviolet      #8a2be2
brown   #a52a2a
burlywood       #deb887
cadetblue       #5f9ea0
chartreuse      #7fff00
chocolate       #d2691e
coral   #ff7f50
cornflowerblue  #6495ed
cornsilk        #fff8dc
crimson #dc143c
cyan #00ffff
darkblue        #00008b
darkcyan        #008b8b
darkgoldenrod   #b8860b
darkgray        #a9a9a9
darkgreen       #006400
darkgrey        #a9a9a9
darkkhaki       #bdb76b
darkmagenta     #8b008b
darkolivegreen  #556b2f
darkorange      #ff8c00
darkorchid      #9932cc
darkred #8b0000
darksalmon      #e9967a
darkseagreen    #8fbc8f
darkslateblue   #483d8b
darkslategray   #2f4f4f
darkslategrey   #2f4f4f
darkturquoise   #00ced1
darkviolet      #9400d3
deeppink        #ff1493
deepskyblue     #00bfff
dimgray #696969
dimgrey #696969
dodgerblue      #1e90ff
firebrick       #b22222
floralwhite     #fffaf0
forestgreen     #228b22
gainsboro       #dcdcdc
ghostwhite      #f8f8ff
gold    #ffd700
goldenrod       #daa520
greenyellow     #adff2f
grey    #808080
honeydew        #f0fff0
hotpink #ff69b4
indianred       #cd5c5c
indigo  #4b0082
ivory   #fffff0
khaki   #f0e68c
lavender        #e6e6fa
lavenderblush   #fff0f5
lawngreen       #7cfc00
lemonchiffon    #fffacd
lightblue       #add8e6
lightcoral      #f08080
lightcyan       #e0ffff
lightgoldenrodyellow    #fafad2
lightgray       #d3d3d3
lightgreen      #90ee90
lightgrey       #d3d3d3
lightpink       #ffb6c1
lightsalmon     #ffa07a
lightseagreen   #20b2aa
lightskyblue    #87cefa
lightslategray  #778899
lightslategrey  #778899
lightsteelblue  #b0c4de
lightyellow     #ffffe0
limegreen       #32cd32
linen   #faf0e6
magenta         #ff00ff
mediumaquamarine        #66cdaa
mediumblue      #0000cd
mediumorchid    #ba55d3
mediumpurple    #9370db
mediumseagreen  #3cb371
mediumslateblue #7b68ee
mediumspringgreen       #00fa9a
mediumturquoise #48d1cc
mediumvioletred #c71585
midnightblue    #191970
mintcream       #f5fffa
mistyrose       #ffe4e1
moccasin        #ffe4b5
navajowhite     #ffdead
oldlace #fdf5e6
olivedrab       #6b8e23
orangered       #ff4500
orchid  #da70d6
palegoldenrod   #eee8aa
palegreen       #98fb98
paleturquoise   #afeeee
palevioletred   #db7093
papayawhip      #ffefd5
peachpuff       #ffdab9
peru    #cd853f
pink    #ffc0cb
plum    #dda0dd
powderblue      #b0e0e6
rosybrown       #bc8f8f
royalblue       #4169e1
saddlebrown     #8b4513
salmon  #fa8072
sandybrown      #f4a460
seagreen        #2e8b57
seashell        #fff5ee
sienna  #a0522d
skyblue #87ceeb
slateblue       #6a5acd
slategray       #708090
slategrey       #708090
snow    #fffafa
springgreen     #00ff7f
steelblue       #4682b4
tan     #d2b48c
thistle #d8bfd8
tomato  #ff6347
turquoise       #40e0d0
violet  #ee82ee
wheat   #f5deb3
whitesmoke      #f5f5f5
yellowgreen     #9acd32
rebeccapurple   #663399
#+END_SRC

** End file

#+BEGIN_SRC
# https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
COLORS = {
  'black': '#000000',
  'silver': '#c0c0c0',
  'gray': '#808080',
  'white': '#ffffff',
  'maroon': '#800000',
  'red': '#ff0000',
  'purple': '#800080',
  'fuchsia': '#ff00ff',
  'green': '#008000',
  'lime': '#00ff00',
  'olive': '#808000',
  'yellow': '#ffff00',
  'navy': '#000080',
  'blue': '#0000ff',
  'teal': '#008080',
  'aqua': '#00ffff',
  'orange': '#ffa500',
  'aliceblue': '#f0f8ff',
  'antiquewhite': '#faebd7',
  'aquamarine': '#7fffd4',
  'azure': '#f0ffff',
  'beige': '#f5f5dc',
  'bisque': '#ffe4c4',
  'blanchedalmond': '#ffebcd',
  'blueviolet': '#8a2be2',
  'brown': '#a52a2a',
  'burlywood': '#deb887',
  'cadetblue': '#5f9ea0',
  'chartreuse': '#7fff00',
  'chocolate': '#d2691e',
  'coral': '#ff7f50',
  'cornflowerblue': '#6495ed',
  'cornsilk': '#fff8dc',
  'crimson': '#dc143c',
  'cyan': '#00ffff',
  'darkblue': '#00008b',
  'darkcyan': '#008b8b',
  'darkgoldenrod': '#b8860b',
  'darkgray': '#a9a9a9',
  'darkgreen': '#006400',
  'darkgrey': '#a9a9a9',
  'darkkhaki': '#bdb76b',
  'darkmagenta': '#8b008b',
  'darkolivegreen': '#556b2f',
  'darkorange': '#ff8c00',
  'darkorchid': '#9932cc',
  'darkred': '#8b0000',
  'darksalmon': '#e9967a',
  'darkseagreen': '#8fbc8f',
  'darkslateblue': '#483d8b',
  'darkslategray': '#2f4f4f',
  'darkslategrey': '#2f4f4f',
  'darkturquoise': '#00ced1',
  'darkviolet': '#9400d3',
  'deeppink': '#ff1493',
  'deepskyblue': '#00bfff',
  'dimgray': '#696969',
  'dimgrey': '#696969',
  'dodgerblue': '#1e90ff',
  'firebrick': '#b22222',
  'floralwhite': '#fffaf0',
  'forestgreen': '#228b22',
  'gainsboro': '#dcdcdc',
  'ghostwhite': '#f8f8ff',
  'gold': '#ffd700',
  'goldenrod': '#daa520',
  'greenyellow': '#adff2f',
  'grey': '#808080',
  'honeydew': '#f0fff0',
  'hotpink': '#ff69b4',
  'indianred': '#cd5c5c',
  'indigo': '#4b0082',
  'ivory': '#fffff0',
  'khaki': '#f0e68c',
  'lavender': '#e6e6fa',
  'lavenderblush': '#fff0f5',
  'lawngreen': '#7cfc00',
  'lemonchiffon': '#fffacd',
  'lightblue': '#add8e6',
  'lightcoral': '#f08080',
  'lightcyan': '#e0ffff',
  'lightgoldenrodyellow': '#fafad2',
  'lightgray': '#d3d3d3',
  'lightgreen': '#90ee90',
  'lightgrey': '#d3d3d3',
  'lightpink': '#ffb6c1',
  'lightsalmon': '#ffa07a',
  'lightseagreen': '#20b2aa',
  'lightskyblue': '#87cefa',
  'lightslategray': '#778899',
  'lightslategrey': '#778899',
  'lightsteelblue': '#b0c4de',
  'lightyellow': '#ffffe0',
  'limegreen': '#32cd32',
  'linen': '#faf0e6',
  'magenta': '#ff00ff',
  'mediumaquamarine': '#66cdaa',
  'mediumblue': '#0000cd',
  'mediumorchid': '#ba55d3',
  'mediumpurple': '#9370db',
  'mediumseagreen': '#3cb371',
  'mediumslateblue': '#7b68ee',
  'mediumspringgreen': '#00fa9a',
  'mediumturquoise': '#48d1cc',
  'mediumvioletred': '#c71585',
  'midnightblue': '#191970',
  'mintcream': '#f5fffa',
  'mistyrose': '#ffe4e1',
  'moccasin': '#ffe4b5',
  'navajowhite': '#ffdead',
  'oldlace': '#fdf5e6',
  'olivedrab': '#6b8e23',
  'orangered': '#ff4500',
  'orchid': '#da70d6',
  'palegoldenrod': '#eee8aa',
  'palegreen': '#98fb98',
  'paleturquoise': '#afeeee',
  'palevioletred': '#db7093',
  'papayawhip': '#ffefd5',
  'peachpuff': '#ffdab9',
  'peru': '#cd853f',
  'pink': '#ffc0cb',
  'plum': '#dda0dd',
  'powderblue': '#b0e0e6',
  'rosybrown': '#bc8f8f',
  'royalblue': '#4169e1',
  'saddlebrown': '#8b4513',
  'salmon': '#fa8072',
  'sandybrown': '#f4a460',
  'seagreen': '#2e8b57',
  'seashell': '#fff5ee',
  'sienna': '#a0522d',
  'skyblue': '#87ceeb',
  'slateblue': '#6a5acd',
  'slategray': '#708090',
  'slategrey': '#708090',
  'snow': '#fffafa',
  'springgreen': '#00ff7f',
  'steelblue': '#4682b4',
  'tan': '#d2b48c',
  'thistle': '#d8bfd8',
  'tomato': '#ff6347',
  'turquoise': '#40e0d0',
  'violet': '#ee82ee',
  'wheat': '#f5deb3',
  'whitesmoke': '#f5f5f5',
  'yellowgreen': '#9acd32',
  'rebeccapurple': '#663399',
}
#+END_SRC

* Replace pattern with 1, 2, 3, ... on each line

For each line replace a search pattern (in this case $) with numbers starting at 1 and then increasing by 1 for each replaced match. a$b$c$ -> a0b1c2

** Start file

#+BEGIN_SRC
I can't see the $ for all the $,
But there $ not $ $ tomorrow.
$ she can do $ and 4,
$ the $ in the $ and $ the $.
#+END_SRC

** End file

#+BEGIN_SRC
I can't see the 1 for all the 2,
But there 1 not 2 3 tomorrow.
1 she can do 2 and 4,
1 the 2 in the 3 and 4 the 5.
#+END_SRC

* From a Thunderlink to a Markdown link

ThunderLinks are durable hyperlinks to specific email messages generated from Thunderbird in HTML format. Leverage the power of vim to make them suitable for a markdown-formatted file.

** Start file

#+BEGIN_SRC
<A HREF="thunderlink://messageid=iFa1.35832.279328.7328107.1571983526.363668.9jW@a2plmmsworker05.prod.iad2.gdg.mail">7 features to increase conversions on your website</A>
#+END_SRC

** End file

#+BEGIN_SRC
[7 features to increase conversions on your website](thunderlink://messageid=iFa1.35832.279328.7328107.1571983526.363668.9jW@a2plmmsworker05.prod.iad2.gdg.mail)
#+END_SRC

* Line under headers

Put a line under each header, and remove the other markdown formatting.
** Start file

#+BEGIN_SRC
## Headers

## To

## Underline
#+END_SRC

** End file

#+BEGIN_SRC
Headers
-------

Are
---

Underlined
----------
#+END_SRC

* Quote modules

Complete golang import statement.

** Start file

#+BEGIN_SRC
import
    encoding/json
    fmt
    math/rand
    net/http
    time

    github.com/graphql-go/graphql
#+END_SRC


** End file

#+BEGIN_SRC
import (
    "encoding/json"
    "fmt"
    "math/rand"
    "net/http"
    "time"

    "github.com/graphql-go/graphql"
)
#+END_SRC

* Levenshtein distance

Compute distance for each pair. Notice that this recursive implementation is very inefficient. Wagner-Fischer algorithm is iterative and much faster. #vimscript

** Start file

#+BEGIN_SRC
" Levenshtein distance between two strings
function! LD(s1, s2)
  let l1 = strlen(a:s1)
  let l2 = strlen(a:s2)
  if l1 <= 0
    return l2
  elseif l2 <= 0
    return l1
  elseif a:s1[0] ==# a:s2[0]
    return LD(a:s1[1:], a:s2[1:])
  else
    return 1 + min([
    \ LD(a:s1, a:s2[1:]), LD(a:s1[1:], a:s2), LD(a:s1[1:], a:s2[1:])
    \ ])
  endif
endfunction
" Humm... Is this useful?
"nmap M I<C-R>=LD("<C-R>a","<C-R>b")<CR><Esc>

"VIM VimGolf
"keystroke matt
"vimscript way
"reformat refactor
"challenge chatter
"colons semicolons
"golfer golfers
"order sorting
"modules models
"shift+ret ctrl+ret
"ninja manic
"destination distance
"pattern lines
"linewrapping linewrapping
"swap switch
"vice versa
"split multiples
"block blackened
"-a-b-c c-a-b
"hello_world hello world!
#+END_SRC

** End file

#+BEGIN_SRC
6
8
9
5
5
4
1
5
2
5
4
7
6
0
4
4
7
5
3
2
#+END_SRC

* Get mail address from outlook format

Create a mail list space separated of mail list formatted by outlook
** Start file

#+BEGIN_SRC
jhon doe <john.doe@mail.com>; alice hoover <alice.hoover@mail.com>; justin teen <jteen@mail.com>;
#+END_SRC

** End file

#+BEGIN_SRC
john.doe@mail.com alice.hoover@mail.com jteen@mail.com
#+END_SRC

* Hogwarts Email Sorting

Given a list of emails, get the students full name and their associated house.
** Start file

#+BEGIN_SRC
james.potter@gryffindor.hogwarts.edu
sirius.black@gryffindor.hogwarts.edu
lily.potter@gryffindor.hogwarts.edu
draco.malfoy@slytherin.hogwarts.edu
harry.potter@gryffindor.hogwarts.edu
susan.bones@hufflepuff.hogwarts.edu
luna.lovegood@ravenclaw.hogwarts.edu
pansy.parkinson@slytherin.hogwarts.edu
cedric.diggory@hufflepuff.hogwarts.edu
cho.chang@hufflepuff.hogwarts.edu
#+END_SRC

** End file

#+BEGIN_SRC
James Potter Gryffindor
Sirius Black Gryffindor
Lily Potter Gryffindor
Draco Malfoy Slytherin
Harry Potter Gryffindor
Susan Bones Hufflepuff
Luna Lovegood Ravenclaw
Pansy Parkinson Slytherin
Cedric Diggory Hufflepuff
Cho Chang Hufflepuff
#+END_SRC

* Data reformat

Reformat this copy-paste data! #csv

** Start file
#+BEGIN_SRC
Place
Location
Like VimGolf
Like Supernatural
Date
Rating
Sex
Field type
Format
Size
Latitude
Longitude

Andorra Andorra la Vella Y Y 20200150 B M 2.050 P 50 42.506317 1.521835
Argentina Buenos Aires N Y 20191225 A M 13.020 S 4 -34.603722 -58.381592
Cuba Cayo Coco Y Y 20040512 C F 2.052 G 10 22.509001 -78.406998
Egypt The Pyramids of Giza N N 20101005 A M 13.202 D 4 29.976480 31.131302
France Provins Y Y 19780729 B M 1.052 C 13 48.560149 3.299203
Italy The Colosseum of Rome Y Y 20020922 C F 5.043 L 7 41.890251 12.492373
Haiti Port-au-Prince N N 19990101 A F 6.058 S 4 18.533333 -72.333336
Kenya Mombasa N Y 20000515 C F 2.011 T 60 -4.043740 39.658871
Maldives Athuruga Island N N 20040331 B F 5.060 H 2 3.887260 72.816154
Monaco Monte Carlo Y N 20200431 C M 1.025 S 4 43.740070 7.426644
Namibia Windhoek Public Library N N 20050528 B F 2.079 U 23 -22.563906 17.085548
Panama Panama Canal Y Y 19970814 C M 5.034 F 6 9.080000 -79.680000
Portugal Santa Cruz Y N 20171011 B F 2.077 H 2 32.688656 -16.791765
Russia The Moscow Kremlin N N 20070216 D M 6.041 X 5 55.752121 37.617664
Switzerland Grand Hotel Kempinski N Y 19950830 C M 9.041 K 6 46.210281, 6.151083
Tunisia El Mourouj Y Y 19961124 B F 2.055 L 7 36.713432 10.209552
Ukraine Odesa Y N 20130413 A M 4.064 G 10 46.469391 30.740883
United States Empire State Building N N 19880202 D F 1.044 X 5 40.748817 -73.985428
#+END_SRC

** End file

#+BEGIN_SRC
Place;Location;Like VimGolf;Like Supernatural;Date;Rating;Sex;Field type;Format;Size;Latitude;Longitude
Andorra;Andorra la Vella;Y;Y;20200150;B;M;2.050;P;50;42.506317;1.521835
Argentina;Buenos Aires;N;Y;20191225;A;M;13.020;S;4;-34.603722;-58.381592
Cuba;Cayo Coco;Y;Y;20040512;C;F;2.052;G;10;22.509001;-78.406998
Egypt;The Pyramids of Giza;N;N;20101005;A;M;13.202;D;4;29.976480;31.131302
France;Provins;Y;Y;19780729;B;M;1.052;C;13;48.560149;3.299203
Italy;The Colosseum of Rome;Y;Y;20020922;C;F;5.043;L;7;41.890251;12.492373
Haiti;Port-au-Prince;N;N;19990101;A;F;6.058;S;4;18.533333;-72.333336
Kenya;Mombasa;N;Y;20000515;C;F;2.011;T;60;-4.043740;39.658871
Maldives;Athuruga Island;N;N;20040331;B;F;5.060;H;2;3.887260;72.816154
Monaco;Monte Carlo;Y;N;20200431;C;M;1.025;S;4;43.740070;7.426644
Namibia;Windhoek Public Library;N;N;20050528;B;F;2.079;U;23;-22.563906;17.085548
Panama;Panama Canal;Y;Y;19970814;C;M;5.034;F;6;9.080000;-79.680000
Portugal;Santa Cruz;Y;N;20171011;B;F;2.077;H;2;32.688656;-16.791765
Russia;The Moscow Kremlin;N;N;20070216;D;M;6.041;X;5;55.752121;37.617664
Switzerland;Grand Hotel Kempinski;N;Y;19950830;C;M;9.041;K;6;46.210281,;6.151083
Tunisia;El Mourouj;Y;Y;19961124;B;F;2.055;L;7;36.713432;10.209552
Ukraine;Odesa;Y;N;20130413;A;M;4.064;G;10;46.469391;30.740883
United States;Empire State Building;N;N;19880202;D;F;1.044;X;5;40.748817;-73.985428
#+END_SRC

* Aliases for cd

Create these beautiful aliases with as few strokes as possible. Are you up for the challenge?

** Start file

#+BEGIN_SRC
alias c.='cd ..'
#+END_SRC

** End file

#+BEGIN_SRC
alias c.='cd ..'
alias c..='cd ../..'
alias c...='cd ../../..'
alias c....='cd ../../../..'
alias c.....='cd ../../../../..'

alias c1='cd ..'
alias c2='cd ../..'
alias c3='cd ../../..'
alias c4='cd ../../../..'
alias c5='cd ../../../../..'
#+END_SRC

* SCREAMING_SNAKE_CASE to Title Case

Convert strings in SCREAMING_SNAKE_CASE to Title Case. Examples: EMPLOYEE_NAME -> Employee Name REVENUE_YEAR_TO_DATE -> Revenue Year To Date SALARY -> Salary

** Start file

#+BEGIN_SRC
EMPLOYEE_NAME

REVENUE_YEAR_TO_DATE

SALARY
#+END_SRC

** End file

#+BEGIN_SRC
Employee Name

Revenue Year To Date

Salary
#+END_SRC

* Reorder the groups

Change the order so that the groups of fruit come before the vegetables.

** Start file

#+BEGIN_SRC
# vegetable
broccoli
spinach
carrot
-
# fruit
peach
plum
-
# vegetable
potato
-
# fruit
apple
banana
-
# vegetable
onion
-
# fruit
watermelon
cherry
-
#+END_SRC

** End file

#+BEGIN_SRC
# fruit
peach
plum
-
# fruit
apple
banana
-
# fruit
watermelon
cherry
-
# vegetable
broccoli
spinach
carrot
-
# vegetable
potato
-
# vegetable
onion
-
#+END_SRC

* Alphabet soup

Create a column of all alphabet characters organized in a funky way
** Start file

#+BEGIN_SRC
a
#+END_SRC

** End file

#+BEGIN_SRC
abcdefghijklmnopqrstuvwxyz
bcdefghijklmnopqrstuvwxyza
cdefghijklmnopqrstuvwxyzab
defghijklmnopqrstuvwxyzabc
efghijklmnopqrstuvwxyzabcd
fghijklmnopqrstuvwxyzabcde
ghijklmnopqrstuvwxyzabcdef
hijklmnopqrstuvwxyzabcdefg
ijklmnopqrstuvwxyzabcdefgh
jklmnopqrstuvwxyzabcdefghi
klmnopqrstuvwxyzabcdefghij
lmnopqrstuvwxyzabcdefghijk
mnopqrstuvwxyzabcdefghijkl
nopqrstuvwxyzabcdefghijklm
opqrstuvwxyzabcdefghijklmn
pqrstuvwxyzabcdefghijklmno
qrstuvwxyzabcdefghijklmnop
rstuvwxyzabcdefghijklmnopq
stuvwxyzabcdefghijklmnopqr
tuvwxyzabcdefghijklmnopqrs
uvwxyzabcdefghijklmnopqrst
vwxyzabcdefghijklmnopqrstu
wxyzabcdefghijklmnopqrstuv
xyzabcdefghijklmnopqrstuvw
yzabcdefghijklmnopqrstuvwx
zabcdefghijklmnopqrstuvwxy
#+END_SRC

* Add string initializers to an enum

Change Typescript enum so that it has string initializers.

** Start file

#+BEGIN_SRC
const enum TestkitType {
  vanilla,
  unidriver,
  protractor,
  puppeteer,
  unknown,
}
#+END_SRC

** End file

#+BEGIN_SRC
const enum TestkitType {
  vanilla = 'VANILLA',
  unidriver = 'UNIDRIVER',
  protractor = 'PROTRACTOR',
  puppeteer = 'PUPPETEER',
  unknown = 'UNKNOWN',
} 
#+END_SRC

* Unsemantic linewrapping

[Inspired by a blog post I read: https://scott.mn/2014/02/21/semantic_linewrapping/. Text adapted.] Sometimes when editing a Markdown file, I wrap the lines semantically. Instead of inserting a newline at 70 columns (or whatever), or making paragraphs one long line, I put in newlines at a point that seems logical to me. This may seem silly, but it produces better diffs. Semantic linewrapping also makes editing snappier. I can delete, edit or insert sentences easily using linewise operations. Code-oriented text editors like Vim and [REDACTED] are really good at this kind of manipulation. Editing text that hasn't been wrapped semantically is a pain, though:

** Start file

#+BEGIN_SRC
Here is a paragraph with some stuff in it. This is the second sentence. This
sentence is really long, and ugly, and the truth is that it basically says
nothing at all. This is the last sentence of the paragraph; thanks for reading!
#+END_SRC

** End file

#+BEGIN_SRC
Here is a paragraph with some stuff in it. This is the second sentence. This is
the last sentence of the paragraph; thanks for reading!
#+END_SRC

* Add quotes to ansible playbook

You created an ansible playbook, but forgot to add quotes. Can you fix it?
** Start file

#+BEGIN_SRC
---
- hosts: all
  vars:
    ssh_state: True
  tasks:
    - name: Manage openssh
      package:
        name: openssh
        state: {{ ssh_state }}
#+END_SRC

** End file

#+BEGIN_SRC
---
- hosts: all
  vars:
    ssh_state: True
  tasks:
    - name: Manage openssh
      package:
        name: openssh
        state: "{{ ssh_state }}"
#+END_SRC

* Just the middle

Delete the instructions at the top and bottom.

** Start file

#+BEGIN_SRC
Leave only the
numbered lines.
LINE 1
LINE 2
LINE 3
That's all.
Thank you
very much.
#+END_SRC

** End file

#+BEGIN_SRC
LINE 1
LINE 2
LINE 3
#+END_SRC

* Bad Copy Syntax

Copy should be from right to left, but sometimes you type it wrong.

** Start file

#+BEGIN_SRC
   copyRtL(source, destination);
   copyRtL("John Q. Public", nameVariable);
#+END_SRC

** End file

#+BEGIN_SRC
   copyRtL(destination, source);
   copyRtL(nameVariable, "John Q. Public");
#+END_SRC

* html paragraph to table

reformat html paragraph to table

** Start file

#+BEGIN_SRC
<div>
<p>task 1</p>
<p>description here ....</p>
<p>task 2</p>
<p>some other description here ....</p>
</div>
#+END_SRC

** End file

#+BEGIN_SRC
<table>
  <tr>
    <td>task 1</td>
    <td>description here ....</td>
  </tr>
  <tr>
    <td>task 2</td>
    <td>some other description here ....</td>
  </tr>
</table>
#+END_SRC

* Reconstruct the actual output from my unit test tool report

When a test fails, my unit test tool reports differences between the actual output and the expected output as follow: - line in the expected output but missing in the actual output are prefixed with a dash - unexpected lines in the actual output are prefixed with a plus sign - comments added by the unit test tool are prefixed with a question mark - common lines are showed `as-is` (well, almost;) From that "diff" format, I would like to reconstruct the actual output.

** Start file

#+BEGIN_SRC
  {'claims': [{'add': '',
-              'mainsnak': {'property': 'P31',
+              'mainsnak': {'datatype': 'wikibase-item',
+                           'datavalue': {'type': 'wikibase-entityid',
+                                         'value': {'entity-type': 'item',
+                                                   'id': 'Q5',
+                                                   'numeric-id': 5}},
+                           'hash': 'ad7d38a03cdd40cdc373de0dc4e7b7fcbccb31d9',
+                           'property': 'P31',
-                           'snaktype': 'value',
+                           'snaktype': 'value'},
?                                              +

-                           'value': {'entity-type': 'item', 'id': 'Q5'}},
+              'qualifiers': {},
               'rank': 'normal',
               'type': 'statement'}],
   'id': 'Q44',
   'ns': 0}
#+END_SRC


** End file

#+BEGIN_SRC
{'claims': [{'add': '',
             'mainsnak': {'datatype': 'wikibase-item',
                          'datavalue': {'type': 'wikibase-entityid',
                                        'value': {'entity-type': 'item',
                                                  'id': 'Q5',
                                                  'numeric-id': 5}},
                          'hash': 'ad7d38a03cdd40cdc373de0dc4e7b7fcbccb31d9',
                          'property': 'P31',
                          'snaktype': 'value'},

             'qualifiers': {},
             'rank': 'normal',
             'type': 'statement'}],
 'id': 'Q44',
 'ns': 0}
#+END_SRC

* Refactor typescript arrow function type

Make arrow function type less verbose and easier to read

** Start file

#+BEGIN_SRC
export const playground: (
  object?: Partial<PlaygroundSection>,
) => PlaygroundSection = config =>
  baseSection({
    type: SectionType.Playground,
    ...config,
  });
#+END_SRC

** End file

#+BEGIN_SRC
export const playground = (
  config?: Partial<PlaygroundSection>,
): PlaygroundSection =>
  baseSection({
    type: SectionType.Playground,
    ...config,
  });
#+END_SRC

* C# data class to F# record

Converting from C# to F# is not hard, but requires some manual labor. Here you should convert from a C# data class to a F# record.

** Start file

#+BEGIN_SRC
public enum State
{
  Active, Inactive
}

public struct Price
{
  public decimal Amount { get; set; }
  public decimal Vat { get; set; }
}

public class Ticket
{
  public State State { get; set; }
  public int Count { get; set; }
  public Price Price { get; set; }
  public DateTime DepartureDate { get; set; }
  public DateTime? ReturnDate { get; set; }
}
#+END_SRC

** End file

#+BEGIN_SRC
type State = Active | Inactive

type Price = {
  amount: decimal
  vat: decimal
}

type Ticket = {
  state: State
  count: int
  price: Price
  departureDate: DateTime
  returnDate: DateTime option
}
#+END_SRC

* Vertical Limit

transform a succession of one word lines to a an array of strings

** Start file

#+BEGIN_SRC
There
is
no
vertical
limit
for
vim
Ninjas
#+END_SRC

** End file

#+BEGIN_SRC
[ "There", "is", "no", "vertical", "limit", "for", "vim", "Ninjas" ]
#+END_SRC

* ASCII-art Histogram

Create an ASCCI-art histogram for the given numbers. Make sure not to leave trailing whitespaces. Thanks to VimGolf I recently discovered a feature of Vim thAT blew my mind. I'm curious to see what real ninjas make of it ;-)

** Start file

#+BEGIN_SRC
 2  4  3  6  5  8  9  7  2  3  1
#+END_SRC

** End file

#+BEGIN_SRC
                  [#]
               [#][#]
               [#][#][#]
         [#]   [#][#][#]
         [#][#][#][#][#]
   [#]   [#][#][#][#][#]
   [#][#][#][#][#][#][#]   [#]
[#][#][#][#][#][#][#][#][#][#]
[#][#][#][#][#][#][#][#][#][#][#]
 2  4  3  6  5  8  9  7  2  3  1
#+END_SRC

* Quote modules (ver.2)

Complete golang import statement.

** Start file

#+BEGIN_SRC
import
    log
    net/http

    graphql github.com/graph-gophers/graphql-go
    github.com/graph-gophers/graphql-go/relay
#+END_SRC

** End file

#+BEGIN_SRC
import (
    "log"
    "net/http"

    graphql "github.com/graph-gophers/graphql-go"
    "github.com/graph-gophers/graphql-go/relay"
)
#+END_SRC

* Add text at some column

Complete golang struct statement.

** Start file

#+BEGIN_SRC
// Product contains information about one product
type Product struct
    ID  int64   id
    Name    string  name
    Info    string  info,omitempty
    Price   float64 price
#+END_SRC

** End file

#+BEGIN_SRC
// Product contains information about one product
type Product struct {
    ID  int64   `json:"id"`
    Name    string  `json:"name"`
    Info    string  `json:"info,omitempty"`
    Price   float64 `json:"price"`
}
#+END_SRC

* calculations

Complete these (weird) calculations.

** Start file

#+BEGIN_SRC
5+11+one=
8*2+one=
100+99+one=
123+123+one=
4+4+two=
12*9+two=
1+1+one=
one+one+one+one=
two*8=
two+two+one+two=
two*two*two*two*two*two*two*two=
two*two*two*two*two*two*two*two*two*two*two*two*two*two*two*two=
#+END_SRC

** End file

#+BEGIN_SRC
5+11+one=17
8*2+one=17
100+99+one=200
123+123+one=247
4+4+two=10
12*9+two=110
1+1+one=3
one+one+one+one=4
two*8=16
two+two+one+two=7
two*two*two*two*two*two*two*two=256
two*two*two*two*two*two*two*two*two*two*two*two*two*two*two*two=65536
#+END_SRC

* change parenthesis

change the pair of braces into a pair of parentheses

** Start file

#+BEGIN_SRC
this is some text {inside a pair of braces} and you need to change it into (brackets)
#+END_SRC

** End file

#+BEGIN_SRC
this is some text (inside a pair of braces) and you need to change it into (brackets)
#+END_SRC
* Song Transcription Oops

When transcribing vocal music to Canjo Tab you can start by finding the lowest note and assigning that to zero and working your way up from there. However, without fail, I tend to miscount the notes and when I am near done I find a lower note. I mark this with a "z". This means I have to increase all the previous ones by 1. just a sting of numbers :)

** Start file

#+BEGIN_SRC
00024432210000024777
664444777642345401222
43210000122243210z0
#+END_SRC

** End file

#+BEGIN_SRC
11135543321111135888
775555888753456512333
5432111123335432101
#+END_SRC

* Remove quotes after first field

Remove the quotes around each field except for the first field.

** Start file

#+BEGIN_SRC
"Livin' on a Prayer, Bon Jovi","89","-5","4FF","212"
"Faith, George Michael","234","49","7E5","22"
"I Still Haven't Found What I'm Looking For, U2","-3","6A2","37","12"
"Walk Like an Egyptian, Bangles","212","433","AEC","-23"
#+END_SRC

** End file

#+BEGIN_SRC
"Livin' on a Prayer, Bon Jovi",89,-5,4FF,212
"Faith, George Michael",234,49,7E5,22
"I Still Haven't Found What I'm Looking For, U2",-3,6A2,37,12
"Walk Like an Egyptian, Bangles",212,433,AEC,-23
#+END_SRC

* Join 'em

This shouldn't be too tough

** Start file

#+BEGIN_SRC
These
words
need
to
be
joined.

Can you help me?
#+END_SRC

** End file

#+BEGIN_SRC
These words need to be joined. Can you help me?
#+END_SRC

* Extract wireshark capture filter

Extract wireshark capture filter from IP plan

** Start file

#+BEGIN_SRC
oam_net               10.81.137.0/29    10.81.137.1-10.81.137.6      10.81.137.6    2300
traffic_net_1         10.81.137.16/28   10.81.137.17-10.81.137.30    10.81.137.30   2301
metallb_default_pool  21.21.0.0/24      21.21.0.1-21.21.0.254        21.21.0.254    -
director_ip           10.81.137.0/29    10.81.137.5-10.81.137.5      10.81.137.6    -
oam_net               10.81.137.8/29    10.81.137.9-10.81.137.14     10.81.137.14   2302
traffic_net_1         10.81.137.32/28   10.81.137.33-10.81.137.46    10.81.137.46   2303
istio_ip_1            10.81.139.1/32    10.81.139.1-10.81.139.1      -              -
#+END_SRC

** End file

#+BEGIN_SRC
net 10.81.137.0/29 or net 10.81.137.16/28 or net 21.21.0.0/24 or net 10.81.137.0/29 or net 10.81.137.8/29 or net 10.81.137.32/28 or net 10.81.139.1/32
#+END_SRC

* Triangle of arrows

I made this by accident when working on another challenge. How would you go about making this?

** Start file

#+BEGIN_SRC
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
=>
#+END_SRC

** End file

#+BEGIN_SRC
=>
=>=>
=>=>=>
=>=>=>=>
=>=>=>=>=>
=>=>=>=>=>=>
=>=>=>=>=>=>=>
=>=>=>=>=>=>=>=>
=>=>=>=>=>=>=>=>=>
=>=>=>=>=>=>=>=>=>=>
=>=>=>=>=>=>=>=>=>
=>=>=>=>=>=>=>=>
=>=>=>=>=>=>=>
=>=>=>=>=>=>
=>=>=>=>=>
=>=>=>=>
=>=>=>
=>=>
=>
#+END_SRC

* Around the clock

You'll want to use 2 special commands to complete this. If you haven't yet, read through 'input.txt', especially :help simple-changes

** Start file

#+BEGIN_SRC
Can you decode my ROTten encrypted message?
uvag: uryc fvzcyr-punatr vf lbhe sevraq!
#+END_SRC

** End file

#+BEGIN_SRC
Can you decode my rotten encrypted message?
hint: HELP SIMPLE-CHANGE is your friend!
#+END_SRC

* Right Align Part of the line

The challenge is to right align a part of the line - this is useful in some SQL queries where it's more clear which are the fields displayed

** Start file

#+BEGIN_SRC
SELECT 
col1 AS column1,
cast(column2 AS varchar(255)) AS column2,
cast(evenlongercolumn3 AS varchar(255)) AS column3,
cast(yetevenlongercolumn4 AS varchar(255)) AS column4,
cast(thelongestcolumnyouhaveeverseen9 AS varchar(255)) AS column5,
col1 AS column6,
cast(column7 AS varchar(255)) AS column7,
cast(evenlongercolumn8 AS varchar(255)) AS column8,
cast(yetevenlongercolumn9 AS varchar(255)) AS column9,
cast(thelongestcolumnyouhaveeverseen10 AS varchar(255)) AS column10
FROM table;
#+END_SRC

** End file

#+BEGIN_SRC
SELECT 
col1                                                    AS column1,
cast(column2 AS varchar(255))                           AS column2,
cast(evenlongercolumn3 AS varchar(255))                 AS column3,
cast(yetevenlongercolumn4 AS varchar(255))              AS column4,
cast(thelongestcolumnyouhaveeverseen9 AS varchar(255))  AS column5,
col1                                                    AS column6,
cast(column7 AS varchar(255))                           AS column7,
cast(evenlongercolumn8 AS varchar(255))                 AS column8,
cast(yetevenlongercolumn9 AS varchar(255))              AS column9,
cast(thelongestcolumnyouhaveeverseen10 AS varchar(255)) AS column10
FROM table;
#+END_SRC

* add line and index

a missed line and index names need to be added

** Start file

#+BEGIN_SRC
ON      OFF     OFF     OFF
OFF     OFF     OFF     OFF
A       OFF     OFF     OFF
A       OFF     OFF     OFF
OFF     A       OFF     OFF
ON      OFF     OFF     OFF
OFF     A       OFF     OFF
OFF     OFF     A       OFF
OUT1
#+END_SRC

** End file

#+BEGIN_SRC
Q1:     ON      OFF     OFF     OFF
Q2:     OFF     OFF     OFF     OFF
Q3:     A       OFF     OFF     OFF
M1:     A       OFF     OFF     OFF
M2:     OFF     A       OFF     OFF
M3:     ON      OFF     OFF     OFF
Q4:     OFF     A       OFF     OFF
M4:     OFF     OFF     A       OFF
BIG:    OFF     OFF     OFF     OFF
RES:    OUT1
#+END_SRC

* Reformat Cura settings

Cura settings are weirdly encoded... After mere replacements, you'll have to enquote two strings (infill_pattern & speed_travel) and dont forget booleans in lowercase. #format #json

** Start file

#+BEGIN_SRC
;SETTING3 "[data]\\n\\ninfill_pattern = gy
;SETTING3 roid\\ninfill_sparse_density = 1
;SETTING3 0\\njerk_print = 10\\nmaterial_p
;SETTING3 rint_temperature = 195\\nretract
;SETTING3 ion_amount = 6\\nretraction_hop_
;SETTING3 enabled = True\\nretraction_hop_
;SETTING3 only_when_collides = True\\nskir
;SETTING3 t_gap = 10\\nskirt_line_count = 
;SETTING3 2\\nspeed_print = 50\\nspeed_tra
;SETTING3 vel = =speed_print if magic_spir
;SETTING3 alize else 120\\n\\n"
#+END_SRC

** End file

#+BEGIN_SRC
{ "infill_pattern": "gyroid", "infill_sparse_density": 10, "jerk_print": 10, "material_print_temperature": 195, "retraction_amount": 6, "retraction_hop_enabled": true, "retraction_hop_only_when_collides": true, "skirt_gap": 10, "skirt_line_count": 2, "speed_print": 50, "speed_travel": "=speed_print if magic_spiralize else 120" }
#+END_SRC

* Change your calendar

Happy New Year!


** Start file

#+BEGIN_SRC
    January 2012
Su Mo Tu We Th Fr Sa
 1  2  3  4  5  6  7
 8  9 10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30 31
#+END_SRC

** End file

#+BEGIN_SRC
    January 2013
Su Mo Tu We Th Fr Sa
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31
#+END_SRC

* Hash staircase

Can you use a strategy to come up with this pattern?

** Start file

#+BEGIN_SRC
#
#+END_SRC


** End file

#+BEGIN_SRC
#####
# # #
#########
# ##### #
#############
# ######### #
#################
# ############# #
#####################
# ################# #
#########################
# ##################### #
#############################
# ######################### #
#################################
# ############################# #
#####################################
# ################################# #
#########################################
# ##################################### #
#############################################
# ######################################### #
#################################################
# ############################################# #
#####################################################
# ################################################# #
#########################################################
# ##################################################### #
#############################################################
# ######################################################### #
#################################################################
# ############################################################# #
#####################################################################
# ################################################################# #
#########################################################################
# ##################################################################### #
#############################################################################
# ######################################################################### #
#################################################################################
# ############################################################################# #
#####################################################################################
# ################################################################################# #
#####################################################################################
#+END_SRC

* Start coding format

I used to start coding with following format: int main(){ -(cursor here) }

** Start file

#+BEGIN_SRC
_
#+END_SRC

** End file

#+BEGIN_SRC
int main(){
    _
}
#+END_SRC

* If-then-else regexp

Rules: - golf is never following golf - vim comes first! Drawing a finite-state machine diagram could help. #regexp

** Start file

#+BEGIN_SRC
vim
golf
vimvim
vimgolf
golfvim
golfgolf
vimvimvim
vimvimgolf
vimgolfvim
vimgolfgolf
golfvimvim
golfvimgolf
golfgolfvim
golfgolfgolf
vimvimvimvim
vimvimvimgolf
vimvimgolfvim
vimvimgolfgolf
vimgolfvimvim
vimgolfvimgolf
vimgolfgolfvim
vimgolfgolfgolf
golfvimvimvim
golfvimvimgolf
golfvimgolfvim
golfvimgolfgolf
golfgolfvimvim
golfgolfvimgolf
golfgolfgolfvim
golfgolfgolfgolf
vimvimvimvimvim
vimvimvimvimgolf
vimvimvimgolfvim
vimvimvimgolfgolf
vimvimgolfvimvim
vimvimgolfvimgolf
vimvimgolfgolfvim
vimvimgolfgolfgolf
vimgolfvimvimvim
vimgolfvimvimgolf
vimgolfvimgolfvim
vimgolfvimgolfgolf
vimgolfgolfvimvim
vimgolfgolfvimgolf
vimgolfgolfgolfvim
vimgolfgolfgolfgolf
golfvimvimvimvim
golfvimvimvimgolf
golfvimvimgolfvim
golfvimvimgolfgolf
golfvimgolfvimvim
golfvimgolfvimgolf
golfvimgolfgolfvim
golfvimgolfgolfgolf
golfgolfvimvimvim
golfgolfvimvimgolf
golfgolfvimgolfvim
golfgolfvimgolfgolf
golfgolfgolfvimvim
golfgolfgolfvimgolf
golfgolfgolfgolfvim
golfgolfgolfgolfgolf
vimvimvimvimvimvim
vimvimvimvimvimgolf
vimvimvimvimgolfvim
vimvimvimvimgolfgolf
vimvimvimgolfvimvim
vimvimvimgolfvimgolf
vimvimvimgolfgolfvim
vimvimvimgolfgolfgolf
#+END_SRC

** End file

#+BEGIN_SRC
yes
no
yes
no
no
no
yes
yes
no
no
no
no
no
no
yes
yes
yes
no
no
no
no
no
no
no
no
no
no
no
no
no
yes
yes
yes
no
yes
yes
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
no
yes
yes
yes
no
yes
yes
no
no
#+END_SRC

* Create Leading Zeros

Create leading zeros only for id columns. Please use generic approach!

** Start file

#+BEGIN_SRC
id      data    age     parent_id
11      "Test"  12      123
123     "Test2  11      null
155     "Test5  19      123
111     "Test"  12      1123
1123    "Test2  11      11
1155    "Test5  19      1123
211     "Test"  12      123
2123    "Test2  11      11
2155    "Test5  19      123
2111    "Test"  12      1123
3123    "Test2  11      11
3155    "Test5  19      1123
1       "root"  9       null
#+END_SRC

** End file

#+BEGIN_SRC
id      data    age     parent_id
0011    "Test"  12      0123
0123    "Test2  11      null
0155    "Test5  19      0123
0111    "Test"  12      1123
1123    "Test2  11      0011
1155    "Test5  19      1123
0211    "Test"  12      0123
2123    "Test2  11      0011
2155    "Test5  19      0123
2111    "Test"  12      1123
3123    "Test2  11      0011
3155    "Test5  19      1123
0001    "root"  9       null
#+END_SRC

* Rule 110

Compute the next 5 iterations of Rule 110 with the given starting state. https://en.wikipedia.org/wiki/Rule_110

** Start file

#+BEGIN_SRC
0000001101110000
#+END_SRC

** End file

#+BEGIN_SRC
0000001101110000
0000011111010000
0000110001110000
0001110011010000
0011010111110000
0111111100010000
#+END_SRC

* C# function to F#

Converting from C# to F# is not hard, but requires some manual labor. Here you should convert a C# function using a C# class to a F# function using a C# class.

** Start file

#+BEGIN_SRC
private static string GetData(Environment environment, string name)
{
  var options = new DefaultOptions();
  if (environment.IsDevelopment())
  {
    options.LocalCredentials = true;
    options.Path = "/stuff";
  }
  else
  {
    options.LocalCredentials = false;
  }
  var uri = new Uri("https://example.com/" + name);
  var client = new GetClient(uri, options);
  return client.GetStuff(name);
}
#+END_SRC


** End file

#+BEGIN_SRC
let getData (environment: Environment) (name: string) : string =
  let options = DefaultOptions()
  if environment.IsDevelopment() then
    options.LocalCredentials <- true
    options.Path <- "/stuff"
  else
    options.LocalCredentials <- false
  let uri = Uri("https://example.com/" + name)
  let client = GetClient(uri, options)
  client.GetStuff(name) 
#+END_SRC

* [Real World] PHP To Markdown

Fun refactoring I had to do in the real world. This presents several challenges: - How to create a table that fits the informations exactly - How to keep track of two informations per line while doing the refactoring - Generate the link from the actual text Have fun!

** Start file

#+BEGIN_SRC
    public const SCHEMA_MAPPED_CONSTRAINTS = [
        Url::class => 'http://schema.org/url',
        Email::class => 'http://schema.org/email',
        Uuid::class => 'http://schema.org/identifier',
        CardScheme::class => 'http://schema.org/identifier',
        Bic::class => 'http://schema.org/identifier',
        Iban::class => 'http://schema.org/identifier',
        Date::class => 'http://schema.org/Date',
        DateTime::class => 'http://schema.org/DateTime',
        Time::class => 'http://schema.org/Time',
        Image::class => 'http://schema.org/image',
        File::class => 'http://schema.org/MediaObject',
        Currency::class => 'http://schema.org/priceCurrency',
        Isbn::class => 'http://schema.org/isbn',
        Issn::class => 'http://schema.org/issn',
    ];
#+END_SRC


** End file

#+BEGIN_SRC
Constraints                                                                           | Vocabulary                        |
--------------------------------------------------------------------------------------|-----------------------------------|
[`Url`](https://symfony.com/doc/current/reference/constraints/Url.html)               | `http://schema.org/url`           |
[`Email`](https://symfony.com/doc/current/reference/constraints/Email.html)           | `http://schema.org/email`         |
[`Uuid`](https://symfony.com/doc/current/reference/constraints/Uuid.html)             | `http://schema.org/identifier`    |
[`CardScheme`](https://symfony.com/doc/current/reference/constraints/CardScheme.html) | `http://schema.org/identifier`    |
[`Bic`](https://symfony.com/doc/current/reference/constraints/Bic.html)               | `http://schema.org/identifier`    |
[`Iban`](https://symfony.com/doc/current/reference/constraints/Iban.html)             | `http://schema.org/identifier`    |
[`Date`](https://symfony.com/doc/current/reference/constraints/Date.html)             | `http://schema.org/Date`          |
[`DateTime`](https://symfony.com/doc/current/reference/constraints/DateTime.html)     | `http://schema.org/DateTime`      |
[`Time`](https://symfony.com/doc/current/reference/constraints/Time.html)             | `http://schema.org/Time`          |
[`Image`](https://symfony.com/doc/current/reference/constraints/Image.html)           | `http://schema.org/image`         |
[`File`](https://symfony.com/doc/current/reference/constraints/File.html)             | `http://schema.org/MediaObject`   |
[`Currency`](https://symfony.com/doc/current/reference/constraints/Currency.html)     | `http://schema.org/priceCurrency` |
[`Isbn`](https://symfony.com/doc/current/reference/constraints/Isbn.html)             | `http://schema.org/isbn`          |
[`Issn`](https://symfony.com/doc/current/reference/constraints/Issn.html)             | `http://schema.org/issn`          |
#+END_SRC

* citizen_hacks_2019_part6

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
//Part 6: A New Hope

event_date = new Date(2019, 9, 28);

while(current_date < event_date){
  let companies = find_companies(contacted_companies);

  //https://stackoverflow.com/questions/5915096/get-random-item-from-javascript-array
  let selected_company = companies[Math.floor(Math.random()*companies.length)];

  request_sponsorship();
  contacted_companies.add();
}

privacy_commissioner_of_canada.grant_accepted(Citizen_Hacks);

//Our first MLH hackathon!
let MLH = require('mlh');

class Citizen_Hacks extends MLH{
  //...
}

//Main Sponsors
CSI_Annex.Sponsor();
Keybase.sponsor();
Feroot.sponsor();
Easy_DNS.sponsor();
Ada.sponsor();

//Other Sponsors
Shirtliff_Hinds_Law.sponsor();
Github.sponsor();
Education_For_Digital_Peace.sponsor();
Fastmail.sponsor();
Mattermost.sponsor();
ProtonMail.sponsor();
Points.sponsor();
Norton_Rose_Fulbright.sponsor();
Waterloo_Engineering_Society.sponsor();
Sticker_Mule.sponsor();

team.find_speakers();
#+END_SRC


** End file

#+BEGIN_SRC
// Part 6: A New Hope

event_date = new Date(2019, 9, 28);

while(current_date < event_date){
  let companies = find_companies(contacted_companies);

  // https://stackoverflow.com/questions/5915096/get-random-item-from-javascript-array
  let selected_company = companies[Math.floor(Math.random()*companies.length)];

  request_sponsorship(selected_company);
  contacted_companies.add(selected_company);
}

privacy_commissioner_of_canada.grant_accepted(Citizen_Hacks);

// Our first MLH hackathon!
let MLH = require('mlh');

class Citizen_Hacks extends MLH{
  // ...
}

// Main Sponsors
CSI_Annex.Sponsor(Citizen_Hacks);
Keybase.sponsor(Citizen_Hacks);
Feroot.sponsor(Citizen_Hacks);
Easy_DNS.sponsor(Citizen_Hacks);
Ada.sponsor(Citizen_Hacks);

// Other Sponsors
Shirtliff_Hinds_Law.sponsor(Citizen_Hacks);
Github.sponsor(Citizen_Hacks);
Education_For_Digital_Peace.sponsor(Citizen_Hacks);
Fastmail.sponsor(Citizen_Hacks);
Mattermost.sponsor(Citizen_Hacks);
ProtonMail.sponsor(Citizen_Hacks);
Points.sponsor(Citizen_Hacks);
Norton_Rose_Fulbright.sponsor(Citizen_Hacks);
Waterloo_Engineering_Society.sponsor(Citizen_Hacks);
Sticker_Mule.sponsor(Citizen_Hacks);

team.find_speakers();
#+END_SRC

* Label grid cells (6x6)

Label the cells of a grid with its coordinates. Rows are labelled top to bottom from A to F, and columns left to right from A to F. Each cell has a coordinate MN, where M is the row letter and N is the column letter.

** Start file

#+BEGIN_SRC

#+END_SRC

** End file

#+BEGIN_SRC
AA AB AC AD AE AF
BA BB BC BD BE BF
CA CB CC CD CE CF
DA DB DC DD DE DF
EA EB EC ED EE EF
FA FB FC FD FE FF
#+END_SRC

* citizen_hacks_2019_challenge1

For the Citizen Hacks 2019 Vim competition
** Start file

#+BEGIN_SRC
citizen hack
#+END_SRC

** End file

#+BEGIN_SRC
citizen hacks
#+END_SRC

* citizen_hacks_2019_challenge2

For the Citizen Hacks 2019 Vim competition.
** Start file

#+BEGIN_SRC
citizen hacks
#+END_SRC

** End file

#+BEGIN_SRC
Citizen HACKS
#+END_SRC

* citizen_hacks_2019_challenge3

For the Citizen Hacks 2019 Vim competition.

** Start file

#+BEGIN_SRC
citizen hacks
#+END_SRC

** End file

#+BEGIN_SRC
hacks
#+END_SRC

* citizen_hacks_2019_challenge5

For the Citizen Hacks 2019 Vim competition.

** Start file

#+BEGIN_SRC
i think that citizen hacks i super fun!
#+END_SRC

** End file

#+BEGIN_SRC
i think that citizen hacks is super fun!
#+END_SRC

* citizen_hacks_2019_challenge6

For the Citizen Hacks 2019 Vim competition.
** Start file
#+BEGIN_SRC
Citizen
Hacks
#+END_SRC

** End file

#+BEGIN_SRC
Citizen Hacks
#+END_SRC

* citizen_hacks_2019_part1

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 1: The Idea

/* The following challenges will cover how Citizen Hacks was created. Good Luck!
Part 1:  The Idea.
Part 2:  Assembling the Team.
Part 3:  Finding Sponsors.
Part 4:  Contacting Sponsors.
Part 5:  Bad News.
Part 6:  A New Hope.
Part 7:  Applications.
Part 8:  Handling Logistics.
Part 9:  The Welcome Party.
*/

const YEAR = 2018

let group = ['Marcel','Mio','Benn']

let add_member = (group, name) => {
  group.push(name);
  console.log(`Added ${name}`);
};

let add_members = (group, names) => {
  names.forEach((name) => {
    add_member(group, name);
  });
};
#+END_SRC

** End file

#+BEGIN_SRC
// Part 1: The Idea

/* The following challenges will cover how Citizen Hacks was created. Good Luck!
CH Part 1: The Idea
CH Part 2: Assembling the Team
CH Part 3: Finding Sponsors
CH Part 4: Contacting Sponsors
CH Part 5: Bad News
CH Part 6: A New Hope
CH Part 7: Applications
CH Part 8: Handling Logistics
CH Part 9: The Welcome Party
*/

const YEAR = 2018;
const MONTH = 'June';

let group = ['Marcel', 'Mio', 'Benn'];

let add_member = (group, name) => {
  group.push(name);
  console.log(`Added ${name}`);
};

let add_members = (group, names) => {
  names.forEach((name) => {
    add_member(group, name);
  });
};
#+END_SRC

* citizen_hacks_2019_part2

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 2: Assembling the Team

// assembling friends
let new_members = ['Daniel', 'Curtis', 'Michael']
add_members(group, new_members)

let fs = require('fs')
let october_diary = JSON.parse(fs.readFileSync('October_2019.json', 'utf8'))

october_diary['school'] = True
october_diary['free_time'] = 'rip'
october_diary['new_friends'] = ['Adam', 'Ahmed', 'Ethan', 'Hrithvik', 'Manvi', 'Sherwin', 'Atif', 'Nick', 'Audrey', 'Mirjana']
add_members(group, october_diary.new_friends)

let team = new CitizenHacks(group)
team.publish_website()
#+END_SRC

** End file

#+BEGIN_SRC
// Part 2: Assembling the Team

// Assembling Friends
let new_members = ['Daniel', 'Curtis', 'Michael', 'Audrey', 'Mirjana'];
add_members(group, new_members);

let fs = require('fs');
let october = JSON.parse(fs.readFileSync('October_2019.json', 'utf8'));

october['school'] = true;
october['free_time'] = 'rip';
october['new_friends'] = ['Adam', 'Ahmed', 'Ethan', 'Hrithvik', 'Manvi', 'Sherwin', 'Atif', 'Nick'];
add_members(group, october.new_friends);

let team = new CitizenHacks(group);
team.publish_website();
#+END_SRC

* citizen_hacks_2019_part3

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 3: Finding Sponsors
let find_companies = (contacted_companies) => {
  let new_companies = [];
  let found = search_google(['privacy_companies', 'security', 'encryptio']);
  found = found.concat(search_google_maps(['Toronto Tech Companies']));
  found = found.concat(search_linkedin(['old_friends', 'new_connections']));
  found.forEach((company) => {
    if(!contacted_companies.has(company)){
      new_companies.push(company);
    }
  });
  return new_companies;
}

let current_date = Date();
let event_date = Date(2018, 11, 23);
let contacted_companies = Set();

while(current_date < event_date){
    let companies = find_companies(contacted_companies);

    // https://stackoverflow.com/questions/5915096/get-random-item-from-javascript-array
    let selected_company = companies[Math.floor(Math.random()*companies.length)];

    request_sponsorship(selected_company);
    contacted_companies.add(selected_company);
}
#+END_SRC

** End file

#+BEGIN_SRC
// Part 3: Finding Sponsors

let find_companies = (contacted_companies) => {
  let new_companies = [];
  let found = search_google(['Privacy Companies', 'Security', 'Encryption']);
  found = found.concat(search_google_maps(['Toronto Tech Companies']));
  found = found.concat(search_linkedin(['Old Friends', 'New Connections']));
  found.forEach((company) => {
    if(!contacted_companies.has(company)) new_companies.push(company);
  });
  return new_companies;
}

let current_date = new Date();
let event_date = new Date(2018, 11, 23);
let contacted_companies = new Set();

while(current_date < event_date){
  let companies = find_companies(contacted_companies);

  // https://stackoverflow.com/questions/5915096/get-random-item-from-javascript-array
  let selected_company = companies[Math.floor(Math.random()*companies.length)];

  request_sponsorship(selected_company);
  contacted_companies.add(selected_company);
}
#+END_SRC
* citizen_hacks_2019_part4

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 4: Contacting Sponsors

const request = require('request');

// Talking to sponsors
let request_sponsorship = (company_name) => {
  // remove
  request(company_name + 'sponsorship_emails', (err, res, reply_body) => {
  // remove
    if(response.statusCode != 200){
  // remove
      console.log(`${company_name} couldn't sponsor us with error:`);
  // remove
      console.log(err);
  // remove
      return;
  // remove
    }
  // remove
    if(details_fuzzy(reply_body)){
  // remove
      team.coordinate_specifics();
  // remove
    }
  // remove
  });
  // remove
};

let details_blurry = (reply) => {
  if(reply.sponsorship_tier == null or reply.reply_contract == 'not_signed' or reply.deliverables = undefined){
    return true;
  }
  return false;
}
#+END_SRC

** End file

#+BEGIN_SRC
// Part 4: Contacting Sponsors

const request = require('request');

// Talking to sponsors
let request_sponsorship = (company_name) => {
  request(company_name + 'sponsorship_emails', (err, res, reply_body) => {
    if(response.statusCode != 200){
      console.log(`${company_name} couldn't sponsor us with error:`);
      console.log(err);
      return;
    }
    if(details_fuzzy(reply_body)){
      team.coordinate_specifics();
    }
  });
};

let details_fuzzy = (reply) => {
  if(reply.sponsorship_tier === null or
     reply.reply_contract === 'not_signed' or
     reply.deliverables === undefined){
    return true;
  }
  return false;
}
#+END_SRC

* citizen_hacks_2019_part9

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 8: The Welcome Party

const http = require('http');

const hostname = 'csi.annex';
const port = 0906;

const server = http.createServer((res, req) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
let welcome = `
Thanks for playing
`;
  res.end(welcome);
});

server.listen(port, hostname, () => {
  console.log(`Nerding out at ${hostname} on ${port}!`);
});
#+END_SRC

** End file

#+BEGIN_SRC
// Part 9: The Welcome Party

const http = require('http');

const hostname = 'csi.annex';
const port = 0906;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
let welcome = `
000000000000000000000000
0  Thanks for playing  0
000123456789987654321000
`;
  res.end(welcome);
});

server.listen(port, hostname, () => {
  console.log(`Nerding out at ${hostname} on ${port}!`);
});
#+END_SRC

* Letters are numbers

Letters and numbers are interchangeable. A lot of programming languages give you simple ways to convert individual letters to hex, binary and decimal but does Vim?

** Start file

#+BEGIN_SRC
Letters can also be numbers. Not sure how it works but it does
#+END_SRC

** End file

#+BEGIN_SRC
761011161161011141153299971103297108115111329810132110117109981011141154632781111163211511711410132104111119321051163211911111410711532981171163210511632100111101115
#+END_SRC

* SFD-ROC: Pipe Dreams

Move the pipes so they match the output.

** Start file

#+BEGIN_SRC

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
|||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
#+END_SRC



** End file

#+BEGIN_SRC
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||

||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| ||||||||| |||||||||
#+END_SRC

** citizen_hacks_2019_part5

For the Citizen Hacks 2019 Vim competition

** Start file

#+BEGIN_SRC
// Part 5: Bad News

break;
venue.secured = false;
const timeLeft = "1 month";

let decideFate = (fate) => {
  switch(fate){
    case "carryOn":
      team.dropOutOfSchool();
      team.getNewJob("citizenHacks");
    case "cancelEvent":
      let brokenHearts = "allOfThem";
    case "postponeEvent":
      let brokenHearts = "allOfThem";
      let hope = "beyondTheHorizon";
  }
}
decide_fate("postpone_event");

/* Our Plan
Month: Jan Study
Month: Feb Study
Month: Mar Study
Month: Apr Study
Month: May Plan
Month: Jun Plan
Month: Jul Plan
Month: Aug Plan
Month: Sep Cross Fingers
*/
#+END_SRC

** End file

#+BEGIN_SRC
// Part 5: Bad News

break;
venue.secured = false;
const time_left = "1 month";

let decide_fate = (fate) => {
  switch(fate){
    case "carry_on":
      team.drop_out_of_school();
      team.get_new_job("Citizen_Hacks");
      break;
    case "cancel_event":
      let broken_hearts = "all_of_them";
      break;
    case "postpone_event":
      let broken_hearts = "all_of_them";
      let hope = "beyond_the_horizon";
      break;
  }
}

decide_fate("postpone_event");

/* Our Plan
Month Jan: Study
Month Feb: Study
Month Mar: Study
Month Apr: Study
Month May: Plan
Month Jun: Plan
Month Jul: Plan
Month Aug: Plan
Month Sep: Cross Fingers
*/
#+END_SRC

* fib.c cleanup

cleanup the file

** Start file

#+BEGIN_SRC
/* Fibonacci Series c language */
#include<stdio.h>
 
main()
{
   int n, first = 0, second = 1, next, c;
 
   printf("Enter the number of terms\n");
   scanf("%d",&n);
 
   printf("First %d terms of Fibonacci series are :-\n",n);
 
   for ( c = 0 ; c < n ; c++ )
   {
      if ( c <= 1 )
         next = c;
      else
      {
         next = first + second;
         first = second;
         second = next;
      }
      printf("%d\n",next);
   }
 
   return 0;
}
#+END_SRC

** End file

#+BEGIN_SRC
/* Fibonacci Series c language */
#include<stdio.h>

main()
{
    int n, first = 0, second = 1, next, c;

    printf("Enter the number of terms\n");
    scanf("%d",&n);

    printf("First %d terms of Fibonacci series are :-\n",n);

    for ( c = 0 ; c < n ; c++ )
    {
        if ( c <= 1 )
            next = c;
        else
        {
            next = first + second;
            first = second;
            second = next;
        }
        printf("%d\n",next);
    }

    return 0;
}
#+END_SRC

* Back to the Future

We can't just time-travel around without first making sure our code is pretty and columns are aligned. And keeping lines with at most 80 characters should help if we ever need to review the code while we're stuck in the past. This is my first challenge. I tried being creative and even did a bit of research, so I hope you enjoy it.

** Start file

#+BEGIN_SRC
#include <TimeTravel.h> // Includes time machine code
#include <DeLorean.h> // Includes DeLorean code

// Defines bool
typedef enum {
        false,
        true
} bool;

// Creates objects
TimeTravel TimeMachine; // Tracks power input, allows jumping in time
DeLorean Vehicle; // Manages the storage, display and input of time, tracks
// speed

long TimeDestination = -2682276364; // Destination time, POSIX
long TimePresent = -2682276364; // Present time
long TimeLast = -2682276364; // Last departed time

unsigned float SpeedCurr = 0.0; // Current speed, in miles per hour
unsigned float SpeedTarget = 88.0; // Target speed

unsigned float PowerCurr = 0.0; // Current power, in gigawatts
unsigned float PowerTarget = 1.21; // Target power

char
loop ()
{
        // Updates local time variables
        TimeDestination = Vehicle.getTime (dtime);
        TimePresent = Vehicle.getTime (ptime);
        TimeLast = Vehicle.getTime (ltime);

        // Updates local speed and power variables
        SpeedCurr = Vehicle.getSpeed ();
        PowerCurr = TimeMachine.getPower ();

        // Get ready statuses
        bool TMReady = TimeMachine.getReady ();
        bool VReady = Vehicle.getReady ();

        // Calculates travel time, in seconds
        long TimeOffset = TimeDestination - TimePresent;

        // Checks speed, power and ready statuses
        if (SpeedCurr >= SpeedTarget && PowerCurr >= PowerTarget && TMReady && VReady) {
                // Prompts for a time travel of given length, checks if no error returned
                if (!TimeMachine.travel (TimeOffset)) {
                        Vehicle.setTime (ltime, TimePresent); // Updates last time with
                        // time as of before traveling
                        Vehicle.setTime (ptime, TimeDestination); // Updates present time with
                        // time as of after traveling
                } else {
                        return 1;
                }
        }

        return 0;
}

char
setup ()
{
        // Begin objects, store errors
        char errTM = TimeMachine.begin ();
        char errV = Vehicle.begin ();

        if (!errTM && !errV)
                return 0;

        return 1;
}

char
main ()
{
        // Runs setup, store error
        char err = setup ();

        // Loops as long as no error
        while (!err) {
                // Run loop, update error
                err = loop ();
        }

        return 1;
}

#+END_SRC

** End file

#+BEGIN_SRC
#include <TimeTravel.h> // Includes time machine code
#include <DeLorean.h>   // Includes DeLorean code

// Defines bool
typedef enum {
        false,
        true
} bool;

// Creates objects
TimeTravel TimeMachine; // Tracks power input, allows jumping in time
DeLorean   Vehicle;     // Manages the storage, display and input of time,
                        // tracks speed

long TimeDestination = -2682276364; // Destination time, POSIX
long TimePresent     = -2682276364; // Present time
long TimeLast        = -2682276364; // Last departed time

unsigned float SpeedCurr   = 0.0;   // Current speed, in miles per hour
unsigned float SpeedTarget = 88.0;  // Target speed

unsigned float PowerCurr   = 0.0;   // Current power, in gigawatts
unsigned float PowerTarget = 1.21;  // Target power

char
loop ()
{
        // Updates local time variables
        TimeDestination = Vehicle.getTime (dtime);
        TimePresent     = Vehicle.getTime (ptime);
        TimeLast        = Vehicle.getTime (ltime);

        // Updates local speed and power variables
        SpeedCurr = Vehicle.getSpeed ();
        PowerCurr = TimeMachine.getPower ();

        // Get ready statuses
        bool TMReady = TimeMachine.getReady ();
        bool VReady  = Vehicle.getReady ();

        // Calculates travel time, in seconds
        long TimeOffset = TimeDestination - TimePresent;

        // Checks speed, power and ready statuses
        if (SpeedCurr >= SpeedTarget && PowerCurr >= PowerTarget &&
            TMReady && VReady) {
                // Prompts for a time travel of given length, checks if no
                // error returned
                if (!TimeMachine.travel (TimeOffset)) {
                        // Updates last time with time as of before traveling
                        Vehicle.setTime (ltime, TimePresent);
                        // Updates present time with time as of after traveling
                        Vehicle.setTime (ptime, TimeDestination);
                } else {
                        return 1;
                }
        }

        return 0;
}

char
setup ()
{
        // Begin objects, store errors
        char errTM = TimeMachine.begin ();
        char errV  = Vehicle.begin ();

        if (!errTM && !errV)
                return 0;

        return 1;
}

char
main ()
{
        // Runs setup, store error
        char err = setup ();

        // Loops as long as no error
        while (!err) {
                // Run loop, update error
                err = loop ();
        }

        return 1;
}
#+END_SRC


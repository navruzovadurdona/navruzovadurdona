- 👋 Hi, I’m @navruzovadurdona
- 👀 I’m interested in various codes
- 🌱 I’m currently learning in ICT4GIRLS in Batken
- 💞️ I’m looking to collaborate on Epam
- 📫 How to reach me +996 (221)-02-80-64
  

<!---
navruzovadurdona/navruzovadurdona is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

3.6.3 (2025.03.09)
Новый

    [TOC] Добавить новый метод слагификации для Zola (#1419). Спасибо, холм (@float3).
    [i18n] Добавить zh-tw переводы (#1499). Спасибо, Уилл 保哥 (@doggy8088).

Исправления

    Исправить конфликт брелокирования с GitHub Copilot NES (#1498). Спасибо, Уилл 保哥 (@doggy8088).

Другие

    [TOC] Обновление метода слагификации для Azure DevOps (#1383). Спасибо, Леви Ричардс (@PHLUNK).
    [GFM] Сделать markdown-it-github-alertsслучай бесчувственный (#1389).#1389 Спасибо, Праз (@prazdevs).
    Поддержите Eclipse Theia IDE (#1442#1442). Спасибо, Макс Якобич (@madmini).

3.6.0/3.6.1/3.6.2 (2024.01.08)
Новый

    [Завершение] Добавить опцию completion.enabledкоторый позволяет повторно включить завершение пути, предусмотренное этим расширением (#1258#1258).
    [Экспорт] Добавить правую кнопочку меню для команды printToHtml(#1278). Спасибо, Дихон Ло (@Andy-Dihong-Luo).
    [Export] Add an option print.pureHtml (#1310).
    [Table formatter] Add range format support (#1361). Thanks, PeaceShi (@peaceshi).
    [List continuation] New onEnterKey logic so as to align with other editors (#1364). Thanks, @HughLink.
    Add action buttons (e.g. toggle bold, italic) to the editor toolbar, you can enable it with a new option showActionButtons (#1358). Thanks, PeaceShi (@peaceshi).
    Support GFM alerts (#1350). Thanks, PraZ (@prazdevs).

Fixes

    Fix when conditions of the closePreview commands/keybindings (#1263).
    Remove the default key binding Alt+c on Mac (#1285)
    [Auto preview] Fix conditions (Jupyter Notebook, VS Code comment widget) of the autoShowPreviewToSide feature (#1288, thanks, Dihong Luo (@Andy-Dihong-Luo)), (#1342).
    [Export] No long convert .md to .html if the links are GitHub urls (#1324).
    [Export] Now correctly convert .md#anchor type links (#1347).
    [List continuation] Check option editor.acceptSuggestionOnEnter (#1367).

    v3.6.2 (2024.01.15) Fix "GFM alerts" exported HTML styles (#1386).

Другие

    [i18n] Update Chinese translations (#1286). Thanks, Dihong Luo (@Andy-Dihong-Luo).

3.5.1 (2023.03.26)
Fixes

    Quarto support, #618 follow-up (#1199). Thanks, Dongdong Kong (@kongdd).
    [List renumbering] Incorrect second-level list renumbering on line delete (#1155).
    [Toggle list] A bug in multi-line case (#1203).
    [HTML] A bug that generates duplicated heading ids (#1232).

Другие

    [i18n] Add Russian translations (#1201). Thanks, Sergey Romanov (@Serhioromano).
    Fix the Shields build status badge (#1215). Thanks, James H (@hughesjs).
    Remove extra spaces when pasting links on selected text (#1245). Thanks, auh (@fanlushuai).
    [Math] KaTeX v0.16.4
    [Completion] Disable path completions as VS Code now has built-in support.
    [Completion] Always exclude .git from completions.

3.5.0 (2022.11.20)
Новый

    [TOC] Use <!-- omit from toc --> to omit a certain section from the table of contents. <!-- omit in toc --> is still supported for backward compatibility (#1118).
    [List continuation] The continuation of task list should now has the same behavior as other editors (#1138). Thanks, @yy0931.
    [List] New option list.toggle.candidate-markers to custom list markers when you use command Toggle list (#1145). Thanks, @petergithub.
    Add a new option bold.indicator so you can use either ** or __ for bold text (#1174). Thanks, @krsche and Samuel Weinhardt (@samuel-weinhardt).
    [R Markdown] Add support for R Markdown and a new option extraLangIds which accepts only rmd and qmd for now. (#618). Thank Dongdong Kong (@kongdd) for #1198.
    [GFM task lists] Checkboxes are now visually enabled but but not clickable (#1189). Thanks, Ian Holst (@ianholst).

Fixes

    Update word pattern for code spans and strikethrough (#1130). Thanks, @Yarakashi-Kikohshi.
    [Syntax decorations] of code spans (#1134, #1135). Thanks, @yy0931.
    [Ordered list renumbering] An issue with sub-list (#1155).
    [HTML] Remove <!-- omit from toc --> comment in the title of the exported HTML (#1175).

Другие

    Code refactoring (#1119). Thanks, @Lemmingh.
    [Math] Update math function completions.
    Add custom context key for onTabKey/onShiftTabKey key binding. There should be less key binding conflicts in the future (#1075). Thanks, @takumisoft68.
    Better blockquote continuation (#1183).
    Reduce extension size by removing unused images (#1161). Thanks, Kid (@kidonng).

3.4.3 (2022.4.24)
Fixes

    [Math] mhchem support (#1116).
    VS Code freezes because of the new word pattern (#1117).

3.4.1 (2022.4.17)

Update 3.4.2: fix dependencies.
Breaking Changes

    [Table formatter] Now you need to escape the pipe character (|) inside table cells, even if it is in a code span. This behavior follows the GFM spec. (#24)

Новый

    [Auto completion] Add .webp files to the image path suggestions (#934).

Fixes

    Resolve Tab conflict when inlineSuggestionVisible, e.g., GitHub Copilot (#665, #1011)
    Multi-cursor list editing (#829, #926).
    You can now add section numbers larger than 99 (#852).
    Resolve keybinding conflict Alt + Shift + Up/Down on Linux (#857)
    TOC with a heading ending with literal # (#867).
    Load extension-contributed scripts asynchronously (#956). Thanks, Jay Park (@phoihos).
    The internal command _wrapBy ignores the after argument (#1051). Thanks, @King-of-Infinite-Space.
    Set vscode-dark class when exporting to HTML with dark theme (#1091). Thanks, Raphael Sander (@raphaelsander).

Другие

    Code health (#869). Thanks to @Lemmingh.
    (Temporary fix) The toggleMath issue with blockquotes (#907).
    Update Japanese translations (#909). Thanks, にせ十字 (@falsecross).
    [Math] Upgrade KaTeX (#943).
    The togglePreview command has been replaced by closePreview (05fb1af).
    Enable virtual workspaces support (limited functionality) (#948, #996)
    Update Markdown word pattern (#1092).
    A few documentation improvements.

3.4.0 (2020.11.14)

    New: New TOC slugify mode azureDevops (#802).

    Fix: Math syntax highlight (#346).
    Fix: Color of the inline code span outline (now using editor.selectionBackground) (#734).
    Fix: Broken TOC links if headings have emoji (#792).
    Fix: Catch exception of other Markdown extensions (#834).
    Fix: Compatibility with Markdown Preview Github Styling.

    Other: Many documentation improvements.
    Other: Automatically build debug.vsix using GitHub Actions (#837).

3.3.0 (2020.08.31)

    New: You can now use <!-- title: Your Title Here --> comment to specify a title of the exported HTML (#506).
    New: Added a toc.slugifyMode option gitea (#763). Thanks, Rodolphe Houdas (@rodolpheh).
    New: Option completion.respectVscodeSearchExclude controlling where to look for file path completions (#789).

    Fix: Failure of toggleList command if there are more than 9 list items (#776).
    Fix: Command togglePreviewToSide wouldn't close the preview tab (#780). Thanks, Anton Tuchkov (@Technik-J).
    Fix: - - - was wrongly treated as a list item (#785).

    Other: Activate extension on command printToHtmlBatch (#769).

3.2.0 (2020.07.25)

    New: [Batch export] command "print documents to HTML" (#594, #747).

    Fix: [HTML export] escape spaces in image path (#731).
    Fix: [TOC] headings with LaTeX (#732).

    Other: A lot of README improvements.

3.1.0 (2020.06.20)

    New: Option print.includeVscodeStylesheets (#726). Thanks, Gluck_S (@Glucksistemi).
    New: Option syntax.decorationFileSizeLimit (#728). Thanks, Rohit Patnaik (@quanticle).

    Fix: Wrong mime type of SVG in exported HTML (#694).
    Fix: Heading numbering issues (#695, #701).
    Fix: TOC issues (#555, #699, #706)
    Fix: Counterintuitive behavior of command checkTaskList (#700).

    Other: README improvements (#709). Thanks, Quang Vu (@vhquang).

3.0.0 (2020.05.24)
Highlights

section numbers

markdown extensions

    Breaking change: Replace toc.githubCompatibility with toc.slugifyMode. Now GitLab-style TOC is supported (#660). Thanks, @BeeeWall.

    New: Command to add/update/remove numbering to headings (#457, #555).
    New: Automatically include other installed Markdown plugins when exporting Markdown to HTML (#658). Thanks, qiqiworld (@1354092549).
    New: The links to .md files will be renamed to .html in the exported HTML (#667).

    Fix: Properly handle Markdown syntax in TOC entries (#654).
    Fix: An issue with workspaceFolders (#666).
    Fix: Slugify function github should downcase also non-Latin characters (#670). Thanks, lesha (@lesha-co).
    Fix: TOC issues (#675, #683).
    Fix: Table formatter fails if there are two identical tables (#682).
    Fix: CJK characters in Markdown Tables (#685).

    Other: Expose wrapBy function (#663).
    Other: README improvements (#681). Thanks, Kaspar (@casaper).

2.8.0 (2020.04.10)

    New: Path auto-completion now respects option search.exclude (#614).
    New: Suggest katex.macros in math environments (#633). Thanks, Y. Ding (@yd278).
    New: Option math.enabled.

    Fix: Escape spaces in file path completions (#590). Thanks, Tomoki Aonuma (@uasi).
    Fix: TOC issues (#593, #603, #629).
    Fix: Table formatter for Thai characters (#602). Thanks, Nutchanon Ninyawee (@CircleOnCircles).
    Fix: Single column table formatting (#604). Thanks, @chnicholas.
    Fix: Issues with option omitFromToc (#644).

    Other: Added Japanese translation (#608). Thanks, にせ十字 (@falsecross).
    Other: Upgraded KaTeX.
    Other: Moved from AppVeyor to GitHub Actions. Thank 雪松 (@yxs) for the CI badge.

2.7.0 (2020.01.11)

    New: Option omittedFromToc (#580). Thanks, Dorian Marchal (@dorian-marchal).

    Fix: Don't continue list item in math environment (#574).
    Fix: HTML entities in TOC (#575).
    Fix: User-defined KaTeX macros weren't included in the exported HTML (#579).
    Fix: Strange HTML tags in the generated TOC (#585).
    Fix: Use %20 for space in URL (#589).

    Other: Update keybindings (#571).
    Other: Disable decorations for large files (threshold 128 KB → 50 KB) (#578).

2.6.1 (2019.12.12)

    Fix: Strange HTML tags in TOC (#567).

2.6.0 (2019.12.08)

    New: Support <!-- omit in toc --> above a heading (#495).
    New: Support <!-- no toc --> above a list (#525).
    New: Option print.theme (#534).
    New: Command "toggle code block" (#551). Thanks, @axiqia.
    New: Support image path completions for HTML img tags.
    New: Include Markdown Footnotes in exported HTML if you have that extension installed (#212).

    Fix: TOC links (#494, #515 and #550).
    Fix: No longer convert images paths with data URIs (#539). Thanks, @leapwill.
    Fix: Unexpected ordered list marker updating (#546). Thanks, Alper Cugun (@alper).
    Fix: Shift + Tab never outdents (#561)

    Other: Update README with high-resolution images.

2.5.0/2.5.1 (2019.10.12)

    New: File path completions (#497). Thanks, @linsui.
    New: Toggle multiple checkboxes (#513). Thanks, @GeorchW.
    New: Option print.validateUrls (#517). Thanks, Olmo Maldonado (@ibolmo).
    New: Add KaTeX mhchem extension (#521). Thanks, Balthild Ires (@balthild).
    New: Option completion.root (#526).

    Fix: Cannot recognize indented headings (#508).
    Fix: TOC and code blocks (#532).

    Other: New logo with white background (#498).
    Other: Remove obsolete HTML attributes (#499).
    Other: Use light theme in exported HTML (#529).

2.4.1/2.4.2 (2019.07.21)

    New: Option toc.downcaseLink (default: true) (#476).

    Fix: KaTeX macros (#473). Thanks, Pierre (@PierreMarchand20).
    Fix: Ignore headings in comments (#462).
    Fix: Magic comment <!-- omit in toc --> was ignored (#490).

    Other: Improve performance for large documents

2.4.0 (2019.06.16)

    New: Command toggleList (Note: no default keybinding assigned) (#237, #307).

    toggle list

    New: Support KaTeX macros (#426). Thanks, Pierre (@PierreMarchand20).

    Fix: Image paths (#415).
    Fix: Fenced code block checking (#434).

    Other: Don't downcase the TOC links (#312). Thanks, Scott Meesseman (@spmeesseman).
    Other: Command toggleMath now cycles through | -> $|$ -> $$\n|\n$$ -> $$ | $$ (#421). Thanks, Li Yiming (@upupming).
    Other: Don't include KaTeX stylesheets in the exported HTML if no math (#430).
    Other: Upgrade KaTeX (#446).
    Other: Better math completions (PR#470, PR#471).

2.3.1 (2019.04.29)

    Fix: Option markdown.extension.print.onFileSave not respected (#432).

2.3.0 (2019.04.28)

    New Prefer unused links for reference link label completions (#414). Thanks, Chris (@alshain).
    New: Option markdown.extension.print.onFileSave (#417). Thanks, Li Yiming (@upupming).
    New: Autocompletion for heading links (#419). Thanks again, Chris (@alshain).

    Fix: Syntax decorations (#390).
    Fix: Table formatter (#408).
    Fix: Delete space rather than outdent list when there are two or more spaces on Backspace (#410)
    Fix: Image paths in exported HTML (#415, #429).
    Fix: TOC and fenced code blocks (#425).

    Other: Sort KaTeX functions (lowercase first) (#413).
    Other: Update KaTeX supported functions (#416). Thanks again, Li Yiming (@upupming).

2.2.0 (2019.03.24)

    Fix: Better syntax decorations (#390, #393).
    Fix: Recognize relative path of markdown.styles when exporting to HTML (#394).
    Other: Unregister formatter when being disabled (#395).
    Other: Better URL regexp (#397). Thanks, Igor (@Ovsyanka).
    Other: Remove default alt + s keybinding for macOS (#404).
    Other: webpack!

2.1.1 (2019.03.05)

    Fix: Table format (#381).
    Fix: Unexpected link creation on pasting (#382).
    Fix: Image path encoding when printing (#385).

2.1.0 (2019.02.16)

    New: Paste link on selected text (#20).

    paste

    New: Multi-cursor support (#33).

    multi-cursor

    New: Auto-complete for reference link IDs (#366).

    suggest ref link

    Fix: Conflict with editor.tabCompletion setting (#367).

    Other: Added ways to buy me a coffee 😉 (PayPal, Alipay or WeChat).

2.0.0 (2019.01.19)

🎂🎂 This extension is 2 years old!

    Новый: Option markdown.extension.list.indentationSize (#344).
        adaptive: use 2 spaces indentation for unordered lists, 3 for ordered lists.
        inherit: respect the tab size setting of current file.
    New: Copy math as TeX command in exported HTML (#358).

    Fix: Many performance issue (#181, #323).
    Fix: Fake heading in YAML front matter (#343).
    Fix: Math function \neq rendering (#252, #349).
    Fix: Keybinding for checking/unchecking task list (#361).
    Fix: Backspace conflicts with Vim extension (#362)
    Fix: GFM table syntax (#316).

Thanks a lot, Li Yiming (@upupming).
1.8.0 (2018.12.08)

    New: Option markdown.extension.toc.tabSize, default auto. Thanks, Maël Valais (@maelvalais).
    Новый: Adaptive indentation size on Tab/ /Backspace key (#155, #241)
    New: Better alignment of cells within tables (#341). Thanks, Sriram Krishna (@k-sriram).

    Fix: Support setext headings in TOC (#284, #311).
    Fix: Markdown preview stylesheets priority (VSCode base styles < VSCode preview settings < Custom stylesheets) (#329).
    Fix: Math completions for untitled document (#326).
    Fix: Image completions (#330).
    Other: Use cmd instead of ctrl for some keybindings on Mac (#334).

1.7.0 (2018.10.27)

    New: Math syntax highlight (#254). Many thanks, @linsui.

    Fix: imgToBase64 option doesn't apply to relative image paths (#266).
    Fix: TOC generation error Cannot read property '1' of null (#275).
    Fix: Escape HTML markup in code blocks (#285).
    Fix: Fix false positive TOC detection (#304).
    Other: Generate HTML with title field (#280).
    Other: Upgrade KaTeX to v0.10.0-rc.1

1.6.3 (2018.10.24)

    Fix: Table formatter

1.6.1 (2018.09.10), 1.6.2 (2018.09.19)

    Fix: for VSCode v1.28.0-insider (and again)
    Other: Remove outline view feature

1.6.0 (2018.07.22)

    New: Add Chinese language support (#240). Thanks, @linsui.
    Fix: Some minor bugs (#205, #223, #231). Thanks, Tom Bresson (@tombresson) for #231.
    Other: More math completions (in fact, all KaTeX function) (#219).

1.5.1 (2018.06.29)

    Fix: Handle activation error for vscode earlier than v1.24.0.

1.5.0 (2018.06.24)

    New: Additional syntax decorations (for strikethrough, code span etc.) and a new plain theme (#185).
    New: Show image preview along with path intellisense (#188).
    Fix: Multi-line task list indentation (#203).
    Fix: Add unique ids to duplicate headings (only when githubCompatibility is true) (#211).
    Other: Upgrade KaTeX version (#196).

v1.5.0 release note
1.4.0 (2018.05.20)

    New: Auto completions! Images paths and math commands
    New: Use comment <!-- omit in toc --> to omit specific heading in TOC (#177).
    New: Option print.imgToBase64, encoding images into HTML file (#73). Thanks, Eric Yancey Dauenhauer (@ericyd).
    Fix: Regression on table formatting (#171). Thanks, Stefan Zi (@StefanZi).
    Fix: Problem of losing track of TOC after editing the first heading (#48).
    Other: Remove quickStylingMode option. (It's default behavior now)
    Other: Provide latest CI build (here).

1.3.0 (2018.05.06)

    New: Automatically fix list markers when editing ordered list (#32, #104, #154). Thanks, Eric Yancey Dauenhauer (@ericyd)
    Новый: Keyboard shortcut for toggling math environment (Ctrl + M) (#165)
    New: Command toggleUnorderedList, switching between non-list, - , * and + (#145)
    Fix: Tables inside list item will be also formatted now (#107). Thanks, Stefan Zi (@StefanZi)
    Fix: Keybinding (Ctrl + K V) conflicts with command workbench.action.terminal.clear (#161)
    Other: Handle Japanese characters when formatting tables (#153). Thanks, Matsuyanagi (@Matsuyanagi)
    Other: Smartly set collapse states when showing outline view (#149)

List Renumbering

list renumbering
Keyboard Shortcut for Toggling Math Environment

math toggle
Toggle Unordered List

(assign your desired key binding to markdown.extension.editing.toggleUnorderedList first)

toggle unordered list
1.2.0 (2018.04.20)

    New: Math rendering! (supported in both vscode preview and exported HTML) (#106)
    New: Option toc.githubCompatibility (in place of removed toc.encodeUri and toc.toLowerCase)
    Fix: Replace underscore with dash when slugifying (#147)
    Other: Add default keybinding Alt + S to command toggleStrikethrough (#91)

1.1.2 (2018.04.04)

    New: Option toc.toLowerCase determining whether or not lowercasing TOC anchors (#136, #137. Thanks, Владислав Люминарский (@Vladislav-Lyuminarskiy))
    Fix: Handle relative CSS paths in markdown.styles setting when printing (#113)
    Fix: TOC now works better with ordered list (#130, #131)
    Fix: Keybinding conflict between togglePreview and paste on Linux (#134)
    Fix: Reveal cursor after editing list in case it is out of view (#138)

1.1.1 (2018.03.24)

    New: Override default "Open Preview" keybinding with "Toggle Preview". Now you can close preview use the same keybinding. (#86)
    Fix: No outline if first-level headiing is missing (#120)
    Fix: List does not continue if a list item starts with URL (#122)
    Fix: print.absoluteImgPath option doesn't take effect on some image tags (#124)
    Fix: A bug when formatting table (#128)

1.1.0 (2018.03.08)

    New: Option toc.encodeUri (#90, #98)
    Fix: TOC detection (#85, #102)
    Fix: Wrong HTML output path if you are editing .MD file (#105)

1.0.5 (2018.02.01)

    Fix: Option markdown.extension.print.absoluteImgPath doesn't work (#84)

1.0.4 (2018.01.29)

    Fix: TOC entries that contain links do not generate correctly (#83)

1.0.3 (2018.01.23)

    New: Option markdown.extension.print.absoluteImgPath (#81)

1.0.2 (2018.01.15)

    Fix: Anchors in exported HTML (#78)

1.0.1 (2018.01.12)

    Fix: Conditions to show outline (#60)
    Fix: Respect insertSpaces and tabSize options of current file when generating TOC (#77)

1.0.0 (2018.01.05)

    New: Update outline view on save (#68)
    New: Option markdown.extension.toc.unorderedList.marker (#74)
    Change: Use Ctrl + Shift + [ (or ]) to change heading level in Mac (#71)
    Fix: Some fixes you might not notice

0.11.2 (2017.11.23)

    New: Option markdown.extension.tableFormatter.enabled (#51)
    Fix: Show outline only when current doc is Markdown (#40)
    Fix: Now option editor.tabCompletion is correctly handled (#55)
    Fix: Now if you export Markdown to HTML, all CSS will be embedded rather than referred (#57)

0.11.1 (2017.11.02)

    Новый: Use Tab/ /Backspace key to indent/outdent task list (#50)

0.11.0 (2017.10.18)

    Новый: Support GFM task lists (checkbox)
        Press Alt + C to check/uncheck a task list item
    New: Add new setting markdown.extension.showExplorer to control whether to show outline view in the explorer panel (Thank you, Ali Karbassi (@karbassi), PR#44)
    Preview: Print to HTML/PDF (work in progress)

0.10.3 (2017.09.30)

    New: Support GFM checkbox when continuing list item (#38)
    Fix: Unexpected deletion of list marker when deleting leading spaces of a list item (#39)

Patches

    v0.10.2: Fix toc == null
    v0.10.1: Update readme

0.10.0 (2017.09.24)

    New: Outline view (#36)
    New: Toggle strikethrough ~~ with the keybinding you like markdown.extension.editing.toggleStrikethrough (#35)
    Fix: Update TOC on save

0.9.0 (2017.09.11)

    New: Multi-cursor support (#33)
    Fix: Support setext heading syntax on TOC generation (#30)
    Fix: Remove backticks in generated TOC link (#29)

0.8.3 (2017.08.17)

    Fix: Respect indentation rules (#9)
    Fix: Handle escaped pipe when formatting GFM table (#28)

0.8.2 (2017.08.07)

    Fix: Handle Chinese characters when formatting table (#26)
    Fix: Use the same slugify function with vscode when creating table of contents (#27)

0.8.1 (2017.07.30)

    New: Support more than 9 list items and some improvements. Thank you @rbolsius
    Fix: Wrong formatting when table contains | (#24)

0.8.0 (2017.07.26)

    New: New setting markdown.extension.quickStyling. Quick styling (toggle bold/italic without selecting words) (default false)
    New: New setting markdown.extension.italic.indicator (* or _)
    New: New setting markdown.extension.toc.levels controlling the range of TOC levels (syntax x..y, default 1..6)
    Other: Add unit tests and continuous integration (Appveyor)

0.7.6/7 (2017.07.18/20)

    Fix: Fix again (activation events). Finally go back to the legacy activation events (not fancy but robust).

0.7.5 (2017.07.15)

    Fix: Cannot activate extension when no folder is opened (#14)

0.7.4 (2017.07.14)

    Fix: Fix activation events (#12)

0.7.3 (2017.07.11)

    Fix: Chinese TOC (#11)

0.7.2 (2017.06.30)

    Fix: Adopt normal Enter, Tab and Backspace behaviors in fenced code blocks (#8)
    Fix: Unexpected list continuing

0.7.1 (2017.06.24)

    Fix: Better TOC detection rules (#7)

0.7.0 (2017.06.10)

    New: GFM table formatter
    Новый: Add shortcuts for code spans (Ctrl + `)
    Новый: Remove empty list item when pressing Enter

0.6.2 (2017.06.07)

    Other: Add marketplace badges; Improve documentation

0.6.1 (2017.05.23)

    Fix: Ctrl + Enter won't break current line now
    Other: Move word completion feature to a standalone extension Dictionary Completion

0.6.0 (2017.05.15)

    Новый: Edit lists with Enter, Tab and Backspace

0.5.2 (2017.04.17)

    Rollback

0.5.1 (2017.04.16)

    New: Automatic close Markdown preview when change editor

0.5.0 (2017.04.13)

    New: New shortcut behavior to let cursor jump out of bold or italic block

Thanks, Zach Kirkland (@zkirkland)
0.4.4 (2017.03.27)

    New: Suggest capitalized words
    Other: More words

0.4.3

    Fix: Word completion, handle ,, ., ...

0.4.2

    Other: Word completion, more words, more accurate

0.4.1

    Fix: Typo

0.4.0 (2017.02.23)

    New: Word completion for frequently used words
    New: Continue quote block >

0.3.0 (2017.02.08)

    New: Print your Markdown to PDF (Need more tests for the installation of required library)
    Новый: At the end of a list item, pressing Enter will automatically insert the new list item bullet
        Blank list item won't be continued
        (Planed: Pressing Tab on the blank list item will indent it) (Help wanted)
    Fix: LF and CRLF in TOC
    Other: Override blockComment (<!--, --> to <!-- ,  -->)

0.2.0 (2017.01.05)

    New: Automatically show preview to side when opening a Markdown file
    New: Option for plain text TOC

0.1.0

    New: Keyboard shortcuts (toggle bold, italic, heading)
    Новый: Table of contents (create, update)
        Options (depth, orderedList, updateOnSave)


このフォルダは、発展版の本文と付録を chapter・section 単位に分割した構成です。

コンパイルするマスター：
  数列の超体系的解説_分割版.tex

chapter_01_intro、chapter_02_recurrence、chapter_03_solving、
chapter_04_appendix が各 chapter のフォルダです。
各 chapter フォルダの中に chapter.tex と section ごとのフォルダがあります。

基本パターンと応用パターンは、chapter_02_recurrence/patterns に
subsection 単位でまとめてあります。それぞれの親 section.tex が
section・subsection の見出しと読み込み順を管理し、patterns 内の子ファイルは
本文だけを担当します。

draft フォルダは今後の草稿用として保持し、本構成の本文からは直接読み込みません。
section_order.txt は、マスターから chapter、chapter から section へ進む読み込み順を示します。
元の発展版ソースや現在の本番付録は、親フォルダ側に保存されています。

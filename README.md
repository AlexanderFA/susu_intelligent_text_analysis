#### Task1 - Regular expressions
#### Task2 - Tokenization
#### Task3 - Typos correction
#### Task4 - Morphology
#### Task5 - Syntactic analysis

Примеры UD-тегов для морфологических атрибутов слов:
* VERB - глагол
* NOUN - существительное
* ADJ - прилагательное
* ADV - наречие
* PRON - местоимение
* NUM - числительное
* ADP - предлог
* CONJ - союз
* PART - частица
* INTJ - междометие
* PUNCT - пунктуационный знак
* SYM - символ (например, математический или валютный символ)
* X - неопределенная или специальная категория
* AUX - вспомогательный глагол
* DET - артикль, местоименное или другое определительное слово

Примеры UD-тегов для синтаксических атрибутов слов:
* nsubj - подлежащее
* obj - дополнение
* iobj - косвенное дополнение
* csubj - подлежащее в придаточном предложении
* ccomp - дополнение в придаточном предложении
* obl - обстоятельство
* advmod - наречие-модификатор
* amod - прилагательное-модификатор
* det - определитель
* case - падеж
* conj - соединительный союз
* mark - вводное слово (например, предлог или союз) в придаточном предложении
* punct - пунктуационный знак
* root - корневой элемент (главное слово) в дереве зависимостей
* dep - зависимое слово, не относящееся к одной из стандартных ролей
* relcl - это сокращение от "relative clause" (относительное предложение) и является одним из синтаксических атрибутов (зависимостей) в структуре дерева зависимостей, используемого в Universal Dependencies (UD) для аннотации текстов.

**relcl** указывает на относительное предложение, которое является зависимым от какого-либо другого слова и выполняет функцию относительного местоимения или относительного наречия в предложении. Например:

`I saw the book that you recommended.`

В этом предложении "that you recommended" является относительным предложением, где "that" - относительное местоимение, а "you recommended" - его зависимость (relcl) от слова "book".
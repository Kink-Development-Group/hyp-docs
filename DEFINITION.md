# **HypnoScript** – Eine esoterische, TypeScript-inspirierte Sprache mit hypnotischem Flair

---

## **Inhaltsverzeichnis**

- [**HypnoScript** – Eine esoterische, TypeScript-inspirierte Sprache mit hypnotischem Flair](#hypnoscript--eine-esoterische-typescript-inspirierte-sprache-mit-hypnotischem-flair)
  - [**Inhaltsverzeichnis**](#inhaltsverzeichnis)
  - [**1. Einleitung**](#1-einleitung)
  - [**2. Grundaufbau**](#2-grundaufbau)
    - [2.1 Lexikalische Struktur](#21-lexikalische-struktur)
    - [2.2 Schlüsselwörter](#22-schlüsselwörter)
    - [2.3 Operatoren und Sonderzeichen](#23-operatoren-und-sonderzeichen)
    - [2.4 Bezeichner (Identifier)](#24-bezeichner-identifier)
    - [2.5 Literale](#25-literale)
  - [**3. Syntax**](#3-syntax)
    - [3.1 Programmstruktur](#31-programmstruktur)
    - [3.2 Deklarationen](#32-deklarationen)
      - [3.2.1 Variablen – `induce`](#321-variablen--induce)
      - [3.2.2 Funktionen – `suggestion`](#322-funktionen--suggestion)
    - [3.3 Kontrollstrukturen](#33-kontrollstrukturen)
      - [3.3.1 Bedingung – `if` / `else`](#331-bedingung--if--else)
      - [3.3.2 Schleifen – `while`, `loop`](#332-schleifen--while-loop)
    - [3.4 Blöcke](#34-blöcke)
    - [3.5 **Erweiterte Konzepte**](#35-erweiterte-konzepte)
      - [3.5.1 Objektorientierung: `session`](#351-objektorientierung-session)
      - [3.5.2 Warte-Mechanismus: `drift(ms)`](#352-warte-mechanismus-driftms)
      - [3.5.3 Hypnotische Operator-Synonyme](#353-hypnotische-operator-synonyme)
      - [3.5.4 Benutzerdefinierte Strukturen/Typen: `tranceify`](#354-benutzerdefinierte-strukturentypen-tranceify)
      - [3.5.5 Weitere Gimmicks (optional)](#355-weitere-gimmicks-optional)
  - [**4. Grammatik (EBNF)**](#4-grammatik-ebnf)
  - [**5. Semantik**](#5-semantik)
    - [5.1 Variablen und Scope](#51-variablen-und-scope)
    - [5.2 Ein- / Ausgabe](#52-ein---ausgabe)
    - [5.3 Turing-Vollständigkeit](#53-turing-vollständigkeit)
  - [**6. Standardbibliothek**](#6-standardbibliothek)
    - [6.1 Tranceify-Bibliothek (Kernfunktionen)](#61-tranceify-bibliothek-kernfunktionen)
    - [6.2 Hypno-Math (Mathematische Funktionen)](#62-hypno-math-mathematische-funktionen)
    - [6.3 StringSpell (String-Manipulation)](#63-stringspell-string-manipulation)
    - [6.4 MemoryPalace (Datenstrukturen)](#64-memorypalace-datenstrukturen)
    - [6.5 TimeWarp (Zeit- und Datumsfunktionen)](#65-timewarp-zeit--und-datumsfunktionen)
    - [6.6 DeepMind (Erweiterte Kontrollstrukturen)](#66-deepmind-erweiterte-kontrollstrukturen)
    - [6.7 SensoryInput (Ein-/Ausgabe-Funktionen)](#67-sensoryinput-ein-ausgabe-funktionen)
  - [**7. Beispielprogramme**](#7-beispielprogramme)
    - [7.1 Einfaches „Hello Trance!"](#71-einfaches-hello-trance)
    - [7.2 Summierung mit Input](#72-summierung-mit-input)
    - [7.3 Verwendung erweiterter Konzepte](#73-verwendung-erweiterter-konzepte)
      - [7.3.1 `session`, `drift`, Operator-Synonyme](#731-session-drift-operator-synonyme)

---

## **1. Einleitung**

**HypnoScript** ist eine minimalistische, esoterische Sprache, die sich an die Syntax von TypeScript/JavaScript anlehnt und dabei alle möglichen Klischees rund um Hypnose, Trance und hypnotische Induktion verwendet.  
Trotz des humorvollen Charakters ist sie auf Turing-Vollständigkeit ausgelegt und unterstützt Variablen, Schleifen, bedingte Anweisungen, Funktionen, Objektorientierung (als _Session-Konzept_) und diverse Sprach-Gimmicks im hypnotischen Stil.

---

## **2. Grundaufbau**

### 2.1 Lexikalische Struktur

- **Groß- und Kleinschreibung**: In dieser Definition gehen wir davon aus, dass Schlüsselwörter case-sensitive sind und stets in **Kleinschreibung** geschrieben werden.  
- **Kommentare**:  
  - Einzeilig: `// Kommentar`  
  - Mehrzeilig: `/* ... */`

### 2.2 Schlüsselwörter

```plaintext
Focus, Relax,
if, else,
while, loop,
snap, sink,
suggestion, awaken, call,
entrance, finale,
deepFocus, deeperStill,
induce, implant, embed,
observe, whisper, command,
trance, subconscious,
from, external,
number, string, boolean,
true, false,
session, constructor,
expose, conceal, dominant,
drift, suspend, freeze,
youAreFeelingVerySleepy, lookAtTheWatch, fallUnderMySpell,
youCannotResist, yourEyesAreGettingHeavy, goingDeeper,
tranceify,
mindLink, sharedTrance,
imperative, trigger, anchor,
oscillate, pendulum,
deepenTrance, emergeFromTrance,
underMyControl, resistanceIsFutile
```

_(Die zusätzlichen hypnotischen Begriffe siehe Kapitel „Erweiterte Konzepte“.)_

### 2.3 Operatoren und Sonderzeichen

- **Zuweisung**: `=`  
- **Arithmetisch**: `+`, `-`, `*`, `/`, `%`  
- **Vergleich**: `==`, `!=`, `>`, `>=`, `<`, `<=` (ergänzt durch hypnotische Synonyme, siehe [3.5.3](#hypnotische-operator-synonyme))  
- **Logisch**: `&&`, `||`, `!`  
- **Trennzeichen/Klammern**: `;`, `,`, `(`, `)`, `{`, `}`, `[` , `]`

### 2.4 Bezeichner (Identifier)

- **Syntax**:  
  - Beginnend mit einem Buchstaben `a-z`/`A-Z` oder `_`  
  - Gefolgt von beliebigen Buchstaben, Ziffern `0-9` oder `_`  

Beispiele: `counter`, `myVar2`, `_hiddenField`.  
Schlüsselwörter dürfen nicht als Bezeichner verwendet werden.

### 2.5 Literale

- **Numerisch**: `42`, `3.14`  
- **String**: `"Hello Trance!"` (Escapes optional, z. B. `\"`)  
- **Boolean**: `true`, `false`  
- _(Optionaler Fantasietyp `trance` hat keine separaten Literale, kann aber als Typannotation dienen.)_

---

## **3. Syntax**

### 3.1 Programmstruktur

Ein einfaches HypnoScript-Programm wird von `Focus { ... } Relax` umschlossen. Innerhalb dieses Blocks stehen Deklarationen, Funktionen und Anweisungen.

Beispiel:

```plaintext
Focus {
    // Programmcode
} Relax
```

Optionale Besonderheit:  

- **`entrance { ... }`** kann als „Startblock“ dienen.  
  - Wenn vorhanden, wird der Code im `entrance`-Block zuerst ausgeführt.  
  - Ist kein `entrance`-Block definiert, wird das Programm z. B. von oben nach unten abgearbeitet oder folgt anderen Implementierungsdetails.

### 3.2 Deklarationen

#### 3.2.1 Variablen – `induce`

```plaintext
induce x: number = 5;
induce y: string = "Hallo";
```

- Mit oder ohne Initialisierung.  
- **Input**: `induce name: string from external;` – kann (fiktiv) einen Wert von außen einlesen.

#### 3.2.2 Funktionen – `suggestion`

```plaintext
suggestion add(a: number, b: number): number {
    awaken a + b;
}
```

- **Aufruf**:  

  ```plaintext
  add(2, 3);
  // oder
  call add(2, 3);
  ```

- **Rückgabe**: `awaken <Ausdruck>;` (analog zu `return`).  

_(Für Funktionen ohne Rückgabewert kann man wahlweise `imperative suggestion` verwenden, siehe [3.5](#erweiterte-konzepte).)_

### 3.3 Kontrollstrukturen

#### 3.3.1 Bedingung – `if` / `else`

```plaintext
if (x > 0) {
    observe "x ist positiv";
} else {
    observe "x ist nicht positiv";
}
```

- **`deepFocus`** als optionaler Ersatz für `{ }`-Blöcke:  

  ```plaintext
  if (counter > 5) deepFocus {
      observe "Counter > 5";
  } else deepFocus {
      observe "Counter <= 5";
  }
  ```

#### 3.3.2 Schleifen – `while`, `loop`

**while**:

```plaintext
while (counter < 10) {
    observe counter;
    counter = counter + 1;
}
```

**loop** (ähnlich `for` in C/JavaScript):

```plaintext
loop (induce i: number = 0; i < 5; i = i + 1) {
    observe i;
}
```

- **`snap;`**: bricht Schleife ab (analog `break`).  
- **`sink;`**: springt zum nächsten Durchlauf (analog `continue`).

### 3.4 Blöcke

- Geschweifte Klammern `{ ... }` oder optional `deepFocus { ... }` als Block.  
- Mehrere Anweisungen können in einem Block stehen.

### 3.5 **Erweiterte Konzepte**

#### 3.5.1 Objektorientierung: `session`

Ermöglicht „Klassen“ in HypnoScript:

```plaintext
session Person {
    expose name: string;
    conceal secretId: number;

    suggestion constructor(newName: string, id: number) {
        this.name = newName;
        this.secretId = id;
    }

    suggestion greet() {
        observe "Hello from " + this.name;
    }
}
```

- **Instanziierung**:

  ```plaintext
  induce p = Person("Alice", 123);
  p.greet();
  ```

- `expose`: Feld/Methoden sind öffentlich (zugreifbar von außen).  
- `conceal`: Feld/Methoden sind privat (nur innerhalb der Session).  
- **`constructor`**: Spezialmethode, die bei Instanzierung aufgerufen wird.  
- **`dominant suggestion`**: (optional) für statische Methoden (z. B. `MathWizard.power(a,b)`).  

#### 3.5.2 Warte-Mechanismus: `drift(ms)`

Fügt eine Verzögerung oder Blockade für `ms` Millisekunden ein:

```plaintext
observe "Starte Hypnose...";
drift(3000);
observe "...Nach 3 Sekunden geht's weiter.";
```

_(Implementierung abhängig von Interpreter/Runtime.)_

#### 3.5.3 Hypnotische Operator-Synonyme

Neben den üblichen `==`, `>`, `<` usw. können folgende Synonyme verwendet werden:

- **`youAreFeelingVerySleepy`** statt `==`  

  ```plaintext
  if (x youAreFeelingVerySleepy y) { ... }
  ```

- **`lookAtTheWatch`** statt `>`  
- **`fallUnderMySpell`** statt `<`  
- **`youCannotResist`** statt `!=`
- **`yourEyesAreGettingHeavy`** statt `>=`
- **`goingDeeper`** statt `<=`
- **`underMyControl`** statt `&&` (logisches UND)
- **`resistanceIsFutile`** statt `||` (logisches ODER)

**Vollständige Liste der hypnotischen Operator-Synonyme:**

| Standard-Operator | Hypnotisches Synonym | Bedeutung |
|-------------------|---------------------|-----------|
| `==` | `youAreFeelingVerySleepy` | Gleichheit |
| `!=` | `youCannotResist` | Ungleichheit |
| `>` | `lookAtTheWatch` | Größer als |
| `<` | `fallUnderMySpell` | Kleiner als |
| `>=` | `yourEyesAreGettingHeavy` | Größer oder gleich |
| `<=` | `goingDeeper` | Kleiner oder gleich |
| `&&` | `underMyControl` | Logisches UND |
| `||` | `resistanceIsFutile` | Logisches ODER |

**Beispiele:**

```plaintext
// Vergleiche mit hypnotischen Synonymen
if (age lookAtTheWatch 18 underMyControl licensed youAreFeelingVerySleepy true) {
    observe "Du darfst fahren!";
}

// Komplexe Bedingung
if (x goingDeeper 100 resistanceIsFutile y yourEyesAreGettingHeavy 50) {
    observe "Bedingung erfüllt!";
}

// Ungleichheit prüfen
if (password youCannotResist "trance123") {
    observe "Falsches Passwort!";
}
```

#### 3.5.4 Benutzerdefinierte Strukturen/Typen: `tranceify`

Erlaubt das Definieren eigener Datensammlungen (Records oder einfache Objekte):

```plaintext
tranceify HypnoRecord {
    name: string;
    age: number;
    isInTrance: boolean;
}

induce r = HypnoRecord {
    name: "Alice",
    age: 30,
    isInTrance: true
};
observe r.name;
```

- Weist Felder per `{ feldname: wert, ... }` zu.  
- Intern kann dies wie eine _struct_ oder ein _Record_ behandelt werden.

#### 3.5.5 Weitere Gimmicks (optional)

- **`imperative suggestion`**: Eine Funktion ohne Rückgabewert (Prozedur).  
- **`mindLink "myLibrary.hyp";`**: Zum Import weiterer Module/Dateien.  
- **`sharedTrance`**: Globale Variablen-Definition.  
- **`trigger`**: Definiert einen Event-Handler oder Callback.
- **`anchor`**: Markiert einen Zustand oder Wert zur späteren Wiederherstellung.
- **`oscillate`**: Wechselt zwischen zwei Zuständen (Toggle-Funktion).
- **`pendulum`**: Führt eine oszillierende Schleife aus (hin und zurück).
- **`suspend`**: Pausiert die Ausführung (ähnlich wie `drift`, aber unbestimmte Zeit).
- **`freeze`**: Macht eine Variable unveränderlich (const).
- **`whisper`**: Ausgabe ohne Zeilenumbruch.
- **`command`**: Imperativ-Form von `observe` für direktive Ausgaben.
- **`implant`**: Alternative zu `induce` für tiefer eingebettete Variablen.
- **`embed`**: Fügt einen Wert in den Subconscious-Speicher ein.
- **`subconscious`**: Zugriff auf versteckte/globale Speicherbereiche.
- **`deepenTrance`**: Erhöht die Trance-Tiefe (könnte Debugging-Level beeinflussen).
- **`emergeFromTrance`**: Verringert die Trance-Tiefe oder beendet bestimmte Modi.
- **`finale`**: Optionaler Abschlussblock (wird nach `Relax` oder am Programmende ausgeführt).

**Beispiele:**

```plaintext
// Trigger-Definition
trigger onValueChange(newValue: number) {
    observe "Wert hat sich geändert zu: " + newValue;
}

// Anchor-Verwendung
induce x: number = 42;
anchor savedX = x;
x = 100;
x = savedX;  // Wiederherstellung

// Oscillate (Toggle)
induce isActive: boolean = false;
oscillate isActive;  // isActive wird zu true
oscillate isActive;  // isActive wird wieder zu false

// Pendulum-Schleife (hin und zurück von 0 bis 10)
pendulum (induce i: number = 0; i fallUnderMySpell 10) {
    observe i;
}

// Freeze-Konstante
freeze PI: number = 3.14159;
// PI = 3.0; // Fehler: Variable ist eingefroren

// Whisper (ohne Zeilenumbruch)
whisper "Bitte warten";
drift(1000);
whisper "...";
drift(1000);
observe "Fertig!";

// Finale-Block
Focus {
    observe "Programmstart";
    
    entrance {
        observe "Initialisierung...";
    }
    
    // Hauptprogramm
    induce result: number = 42;
    observe "Ergebnis: " + result;
    
    finale {
        observe "Aufräumen und Beenden...";
        observe "Programm erfolgreich beendet.";
    }
} Relax
```

- **Sprünge** (Goto-ähnlich):  

  ```plaintext
  myLabel:
  observe "Label erreicht!";
  if (x < 10) sinkTo myLabel; 
  ```

  _(Extremes Feature – kann, muss aber nicht verwendet werden.)_

---

## **4. Grammatik (EBNF)**

Nachfolgend eine beispielhafte EBNF-Skizze, die die Kernsyntax (ohne alle Operator-Synonyme) abbildet. Die Synonyme (`youAreFeelingVerySleepy`, etc.) könnten in der Praxis direkt auf die Standardoperatoren gemappt werden.

```ebnf
Program         ::= "Focus" Block [ FinaleBlock ] "Relax" ;

Block           ::= { Statement } ;

Statement       ::= VarDeclarationStatement
                  | FreezeStatement
                  | ExpressionStatement
                  | IfStatement
                  | WhileStatement
                  | LoopStatement
                  | PendulumStatement
                  | BreakStatement
                  | ContinueStatement
                  | FunctionDeclaration
                  | ReturnStatement
                  | ObserveStatement
                  | WhisperStatement
                  | CommandStatement
                  | EntranceBlock
                  | SessionDeclaration
                  | TranceifyDeclaration
                  | BlockStatement
                  | AnchorStatement
                  | OscillateStatement
                  | DriftStatement
                  ;

BlockStatement  ::= ("deepFocus" | "deeperStill" |) "{" { Statement } "}" 
                  ;

EntranceBlock   ::= "entrance" BlockStatement ;
FinaleBlock     ::= "finale" BlockStatement ;

VarDeclarationStatement
                  ::= ("induce" | "implant" | "embed") Identifier [ ":" Type ] [ "=" Expression ] ";"
                  | ("induce" | "implant") Identifier [ ":" Type ] "from" "external" ";" ;

FreezeStatement ::= "freeze" Identifier ":" Type "=" Expression ";" ;

ObserveStatement
                  ::= "observe" Expression ";" ;

WhisperStatement
                  ::= "whisper" Expression ";" ;

CommandStatement
                  ::= "command" Expression ";" ;

DriftStatement  ::= ("drift" | "suspend") "(" Expression ")" ";" ;

AnchorStatement ::= "anchor" Identifier "=" Expression ";" ;

OscillateStatement
                  ::= "oscillate" Identifier ";" ;

PendulumStatement
                  ::= "pendulum" "(" [ VarDeclarationStatementNoSemicolon ] 
                                   ";" Expression ";" Expression ")"
                      BlockStatement ;

IfStatement     ::= "if" "(" Expression ")" BlockStatement
                    [ "else" BlockStatement ] ;

WhileStatement  ::= "while" "(" Expression ")" BlockStatement ;

LoopStatement   ::= "loop" "(" [ VarDeclarationStatementNoSemicolon ] 
                             ";" Expression ";" Expression ")"
                    BlockStatement ;

BreakStatement  ::= "snap" ";" ;
ContinueStatement
                  ::= "sink" ";" ;

FunctionDeclaration
                  ::= ( "suggestion" | "imperative suggestion" | "dominant suggestion" )
                      Identifier "(" [ ParameterList ] ")" [ ":" Type ]
                      BlockStatement ;

ParameterList   ::= Parameter { "," Parameter } ;
Parameter       ::= Identifier [ ":" Type ] ;

ReturnStatement ::= "awaken" [ Expression ] ";" ;

ExpressionStatement
                  ::= Expression ";" ;

Expression      ::= AssignmentExpression ;

AssignmentExpression
                  ::= LogicalOrExpression [ "=" AssignmentExpression ] ;

LogicalOrExpression
                  ::= LogicalAndExpression
                      { ( "||" | "resistanceIsFutile" ) LogicalAndExpression } ;

LogicalAndExpression
                  ::= EqualityExpression
                      { ( "&&" | "underMyControl" ) EqualityExpression } ;

EqualityExpression
                  ::= RelationalExpression
                      { ( "==" | "!=" 
                          | "youAreFeelingVerySleepy" | "youCannotResist" ) 
                          RelationalExpression } ;

RelationalExpression
                  ::= AdditiveExpression
                      { ( ">" | ">=" | "<" | "<=" 
                          | "lookAtTheWatch" | "yourEyesAreGettingHeavy"
                          | "fallUnderMySpell" | "goingDeeper" ) 
                          AdditiveExpression } ;

AdditiveExpression
                  ::= MultiplicativeExpression
                      { ( "+" | "-" ) MultiplicativeExpression } ;

MultiplicativeExpression
                  ::= UnaryExpression
                      { ( "*" | "/" | "%" ) UnaryExpression } ;

UnaryExpression ::= [ ("+" | "-" | "!") ] PrimaryExpression ;

PrimaryExpression
                  ::= Identifier
                  | Literal
                  | "(" Expression ")"
                  | FunctionCall
                  ;

FunctionCall    ::= [ "call" ] Identifier "(" [ ArgumentList ] ")" ;

ArgumentList    ::= Expression { "," Expression } ;

SessionDeclaration
                  ::= "session" Identifier "{" { SessionMember } "}" ;

SessionMember   ::= ( "expose" | "conceal" )? 
                    ( VarDeclarationStatementNoSemicolon 
                      | FunctionDeclaration 
                      | ConstructorDeclaration ) ;

ConstructorDeclaration
                  ::= "suggestion" "constructor" "(" [ ParameterList ] ")" 
                      BlockStatement ;

TranceifyDeclaration
                  ::= "tranceify" Identifier "{" { VarDefinition } "}" ;

VarDefinition   ::= Identifier ":" Type ";" ;

VarDeclarationStatementNoSemicolon
                  ::= ("induce" | "implant" | "embed") Identifier [ ":" Type ] [ "=" Expression ]
                  | ("induce" | "implant") Identifier [ ":" Type ] "from" "external" ;

Literal         ::= NumericLiteral
                  | StringLiteral
                  | BooleanLiteral ;

NumericLiteral  ::= Digit { Digit } [ "." Digit { Digit } ] ;
StringLiteral   ::= '"' { <char außer '"' oder Zeilenumbruch> } '"' ;
BooleanLiteral  ::= "true" | "false" ;

Type            ::= "number" | "string" | "boolean" | "trance"
                  | Identifier ; // Für benutzerdefinierte Typen, struct-Namen etc.

Digit           ::= [0-9] ;
```

---

## **5. Semantik**

### 5.1 Variablen und Scope

- **`induce varName: type = expr;`**: Deklariert eine lokale Variable im aktuellen Block.  
- **Gültigkeit**: Variablen sind innerhalb des Blockes und seiner Unterblöcke sichtbar (lexikalischer Scope).  
- **Zuweisung**: `varName = expr;` ändert den Wert einer bereits deklarierten Variable.  
- **Eingabe**: `from external` simuliert Benutzer-/Dateiinput (Implementation abhängig).

### 5.2 Ein- / Ausgabe

- **`observe expr;`**: Gibt den Wert von `expr` (z. B. String, Zahl, boolean) an das „Trance-Log“ aus (Konsole, UI, etc.).  
- **`drift(ms);`**: Unterbricht / pausiert den Programmfluss (themenbedingt „Verzögerung in Trance“).  

### 5.3 Turing-Vollständigkeit

- **Schleifen (while, loop)** bzw. **Rekursion** ermöglichen beliebig lange bzw. wiederholende Prozesse.  
- **Bedingte Verzweigungen (if/else)** erlauben dynamische Pfadwahl.  
- **Variablen** speichern veränderbare Werte.  

Diese Faktoren reichen aus, um Turing-Vollständigkeit zu gewährleisten.

---

## **6. Standardbibliothek**

Die HypnoScript-Standardbibliothek bietet eine umfassende Sammlung von hypnotisch benannten Funktionen und Modulen, die häufige Programmieraufgaben vereinfachen. Alle Bibliotheksfunktionen folgen dem hypnotischen Thema und verwenden suggestive Bezeichnungen.

### 6.1 Tranceify-Bibliothek (Kernfunktionen)

Die Kernbibliothek stellt grundlegende Funktionen für Typkonvertierung und Basisdatenmanipulation bereit.

```plaintext
// Typkonvertierungen
suggestion toNumber(value: string): number
suggestion toString(value: number): string
suggestion toBoolean(value: any): boolean

// Typ-Prüfungen
suggestion isNumber(value: any): boolean
suggestion isString(value: any): boolean
suggestion isBoolean(value: any): boolean
suggestion isTranced(value: any): boolean  // Prüft, ob Wert in "Trance" ist (null/undefined)

// Grundlegende Utilities
suggestion clone(obj: any): any  // Tiefe Kopie eines Objekts
suggestion absorb(target: any, source: any): any  // Merge von Objekten (hypnotisches "merge")
suggestion reflect(value: any): string  // Gibt Typ-Information zurück
```

**Beispiel:**

```plaintext
Focus {
    induce numStr: string = "42";
    induce num: number = toNumber(numStr);
    observe "Konvertiert: " + num;
    
    if (isNumber(num)) {
        observe "Es ist eine Zahl!";
    }
} Relax
```

### 6.2 Hypno-Math (Mathematische Funktionen)

Das Hypno-Math-Modul bietet erweiterte mathematische Funktionen mit hypnotischen Namen.

```plaintext
// Grundlegende Operationen
suggestion power(base: number, exponent: number): number  // Potenzierung
suggestion squareRoot(n: number): number  // Quadratwurzel (visualisiere die Spirale...)
suggestion absoluteDepth(n: number): number  // Absolutwert (Tiefe ist immer positiv)

// Rundungsfunktionen
suggestion ceiling(n: number): number  // Aufrunden (aufsteigen aus der Trance)
suggestion floor(n: number): number  // Abrunden (sinken in die Trance)
suggestion roundToNearest(n: number): number  // Runden zur nächsten Ganzzahl

// Trigonometrische Funktionen (Pendel-Bewegungen)
suggestion pendulumSin(angle: number): number  // sin
suggestion pendulumCos(angle: number): number  // cos
suggestion pendulumTan(angle: number): number  // tan

// Erweiterte Funktionen
suggestion spiralLog(n: number): number  // Logarithmus (Spirale nach innen)
suggestion spiralExp(n: number): number  // Exponentialfunktion (Spirale nach außen)
suggestion hypnoticPi(): number  // π (3.14159...)
suggestion hypnoticE(): number   // e (2.71828...)

// Min/Max (Dominant/Submissive Auswahl)
suggestion selectDominant(a: number, b: number): number  // max
suggestion selectSubmissive(a: number, b: number): number  // min
suggestion clampBetween(value: number, min: number, max: number): number  // Begrenzt Wert

// Zufallsfunktionen (Unbewusste Entscheidungen)
suggestion unconsciousChoice(): number  // Zufallszahl zwischen 0 und 1
suggestion unconsciousInt(min: number, max: number): number  // Zufallsganzzahl
suggestion unconsciousBool(): boolean  // Zufälliger boolean
```

**Beispiel:**

```plaintext
Focus {
    induce radius: number = 5.0;
    induce area: number = hypnoticPi() * power(radius, 2);
    observe "Kreisfläche: " + area;
    
    induce angle: number = 45.0;
    induce sine: number = pendulumSin(angle);
    observe "Sinus von " + angle + " Grad: " + sine;
    
    induce randomNum: number = unconsciousInt(1, 100);
    observe "Zufällige Zahl: " + randomNum;
} Relax
```

### 6.3 StringSpell (String-Manipulation)

StringSpell bietet mächtige String-Manipulationsfunktionen mit hypnotischen Metaphern.

```plaintext
// Länge und Zugriff
suggestion measureDepth(str: string): number  // Länge des Strings
suggestion extractEssence(str: string, index: number): string  // Zeichen an Position
suggestion sliceMemory(str: string, start: number, end: number): string  // Substring

// Suchen und Ersetzen
suggestion findPattern(str: string, pattern: string): number  // indexOf
suggestion containsPattern(str: string, pattern: string): boolean  // includes
suggestion replaceMemory(str: string, old: string, new: string): string  // replace
suggestion replaceAllMemories(str: string, old: string, new: string): string  // replaceAll

// Transformation
suggestion toUpper(str: string): string  // In Großbuchstaben (LAUTER BEFEHL)
suggestion toLower(str: string): string  // In Kleinbuchstaben (sanftes Flüstern)
suggestion trimEdges(str: string): string  // Entfernt Whitespace an den Rändern
suggestion reverseTrance(str: string): string  // Kehrt String um

// Zerlegung und Zusammenfügung
suggestion fragmentMemory(str: string, delimiter: string): string[]  // split
suggestion mergeThoughts(arr: string[], separator: string): string  // join
suggestion repeatMantra(str: string, times: number): string  // String wiederholen

// Prüfungen
suggestion startsWithSuggestion(str: string, prefix: string): boolean
suggestion endsWithAwakening(str: string, suffix: string): boolean
suggestion matchesPattern(str: string, regex: string): boolean  // Regex-Match
```

**Beispiel:**

```plaintext
Focus {
    induce message: string = "  Willkommen in der Trance  ";
    induce cleaned: string = trimEdges(message);
    observe cleaned;
    
    induce words: string[] = fragmentMemory(cleaned, " ");
    observe "Anzahl Wörter: " + measureDepth(words);
    
    induce mantra: string = repeatMantra("Om ", 3);
    observe mantra;  // "Om Om Om "
    
    induce reversed: string = reverseTrance("Trance");
    observe reversed;  // "ecnarT"
} Relax
```

### 6.4 MemoryPalace (Datenstrukturen)

MemoryPalace bietet Funktionen für Arrays und erweiterte Datenstrukturen.

```plaintext
// Array-Grundfunktionen
suggestion createVault(size: number): any[]  // Erstellt Array mit Größe
suggestion storeMemory(arr: any[], value: any): number  // push - gibt neue Länge zurück
suggestion retrieveLastMemory(arr: any[]): any  // pop
suggestion peekAtMemory(arr: any[], index: number): any  // Array-Zugriff
suggestion implantMemory(arr: any[], index: number, value: any)  // Setze Wert an Index

// Array-Manipulation
suggestion reverseMemories(arr: any[]): any[]  // Kehrt Array um
suggestion sortMemories(arr: any[]): any[]  // Sortiert Array
suggestion filterMemories(arr: any[], predicate: suggestion): any[]  // filter
suggestion mapMemories(arr: any[], transformer: suggestion): any[]  // map
suggestion reduceToEssence(arr: any[], reducer: suggestion, initial: any): any  // reduce

// Array-Suche
suggestion findMemory(arr: any[], value: any): number  // indexOf
suggestion containsMemory(arr: any[], value: any): boolean  // includes
suggestion countOccurrences(arr: any[], value: any): number  // Zählt Vorkommen

// Array-Info
suggestion vaultSize(arr: any[]): number  // Länge
suggestion isEmptyVault(arr: any[]): boolean  // Ist leer
suggestion firstMemory(arr: any[]): any  // Erstes Element
suggestion lastMemory(arr: any[]): any  // Letztes Element

// Erweiterte Strukturen (Maps/Dictionaries)
session MemoryMap {
    expose suggestion constructor()
    expose suggestion store(key: string, value: any)
    expose suggestion retrieve(key: string): any
    expose suggestion forget(key: string)
    expose suggestion hasKey(key: string): boolean
    expose suggestion allKeys(): string[]
    expose suggestion allValues(): any[]
}

// Stack (LIFO)
session MindStack {
    expose suggestion constructor()
    expose suggestion push(value: any)
    expose suggestion pop(): any
    expose suggestion peek(): any
    expose suggestion isEmpty(): boolean
    expose suggestion size(): number
}

// Queue (FIFO)
session ThoughtQueue {
    expose suggestion constructor()
    expose suggestion enqueue(value: any)
    expose suggestion dequeue(): any
    expose suggestion isEmpty(): boolean
    expose suggestion size(): number
}
```

**Beispiel:**

```plaintext
Focus {
    // Array-Operationen
    induce memories: number[] = [1, 2, 3, 4, 5];
    induce doubled = mapMemories(memories, suggestion(x: number): number {
        awaken x * 2;
    });
    observe doubled;  // [2, 4, 6, 8, 10]
    
    // Stack verwenden
    induce stack = MindStack();
    stack.push(10);
    stack.push(20);
    stack.push(30);
    observe stack.pop();  // 30
    observe stack.peek();  // 20
    
    // Map verwenden
    induce map = MemoryMap();
    map.store("name", "Alice");
    map.store("age", 30);
    observe map.retrieve("name");  // "Alice"
} Relax
```

### 6.5 TimeWarp (Zeit- und Datumsfunktionen)

TimeWarp ermöglicht Zeit- und Datumsmanipulation mit hypnotischen Konzepten.

```plaintext
// Aktuelle Zeit
suggestion nowInTrance(): number  // Aktuelle Timestamp (Millisekunden seit Epoch)
suggestion currentMoment(): string  // Aktuelles Datum/Zeit als String

// Zeit-Manipulation
suggestion pauseReality(ms: number)  // Entspricht drift(ms) - pausiert Ausführung
suggestion accelerateTime(factor: number)  // Beschleunigt nachfolgende Operationen (konzeptionell)
suggestion decelerateTime(factor: number)  // Verlangsamt nachfolgende Operationen

// Datum-Parsing und Formatierung
suggestion parseTimeMoment(dateStr: string): number  // String zu Timestamp
suggestion formatTimeMoment(timestamp: number, format: string): string  // Timestamp zu formatiertem String

// Datum-Arithmetik
suggestion addDays(timestamp: number, days: number): number
suggestion addHours(timestamp: number, hours: number): number
suggestion addMinutes(timestamp: number, minutes: number): number
suggestion differenceInDays(ts1: number, ts2: number): number
suggestion differenceInHours(ts1: number, ts2: number): number

// Datum-Komponenten
suggestion extractYear(timestamp: number): number
suggestion extractMonth(timestamp: number): number
suggestion extractDay(timestamp: number): number
suggestion extractHour(timestamp: number): number
suggestion extractMinute(timestamp: number): number
suggestion extractSecond(timestamp: number): number
```

**Beispiel:**

```plaintext
Focus {
    induce now: number = nowInTrance();
    observe "Aktueller Timestamp: " + now;
    
    induce tomorrow: number = addDays(now, 1);
    induce formatted: string = formatTimeMoment(tomorrow, "YYYY-MM-DD");
    observe "Morgen: " + formatted;
    
    pauseReality(2000);  // Warte 2 Sekunden
    observe "2 Sekunden später...";
} Relax
```

### 6.6 DeepMind (Erweiterte Kontrollstrukturen)

DeepMind bietet erweiterte Kontrollfluss- und Funktionskompositionswerkzeuge.

```plaintext
// Wiederholungen mit Callbacks
suggestion repeatAction(times: number, action: suggestion)
suggestion repeatUntil(condition: suggestion, action: suggestion)
suggestion repeatWhile(condition: suggestion, action: suggestion)

// Verzögerte Ausführung
suggestion delayedSuggestion(action: suggestion, delayMs: number)
suggestion scheduleAwakening(action: suggestion, timestamp: number)

// Funktionskomposition
suggestion compose(f: suggestion, g: suggestion): suggestion  // f(g(x))
suggestion pipe(f: suggestion, g: suggestion): suggestion     // g(f(x))
suggestion curry(f: suggestion, arg: any): suggestion         // Partial application

// Bedingte Ausführung
suggestion ifTranced(condition: boolean, thenAction: suggestion, elseAction: suggestion)
suggestion switchMindState(value: any, cases: MemoryMap, defaultCase: suggestion)

// Fehlerbehandlung (Awakening from Nightmare)
suggestion tryOrAwaken(action: suggestion, recoveryAction: suggestion)
suggestion ensureAwakening(action: suggestion, cleanupAction: suggestion)  // try-finally

// Async/Concurrency (Parallele Trancen)
suggestion parallelTrance(actions: suggestion[])  // Führt mehrere Aktionen parallel aus
suggestion sequentialTrance(actions: suggestion[])  // Führt Aktionen nacheinander aus
```

**Beispiel:**

```plaintext
Focus {
    // Wiederhole eine Aktion 5 mal
    repeatAction(5, suggestion() {
        observe "In Trance...";
    });
    
    // Verzögerte Ausführung
    observe "Vor der Verzögerung";
    delayedSuggestion(suggestion() {
        observe "Nach 3 Sekunden";
    }, 3000);
    
    // Bedingte Ausführung
    induce x: number = 10;
    ifTranced(x lookAtTheWatch 5, 
        suggestion() { observe "x ist größer als 5"; },
        suggestion() { observe "x ist nicht größer als 5"; }
    );
} Relax
```

### 6.7 SensoryInput (Ein-/Ausgabe-Funktionen)

SensoryInput erweitert die Ein- und Ausgabemöglichkeiten von HypnoScript.

```plaintext
// Ausgabe-Funktionen
suggestion observe(message: any)  // Standard-Ausgabe mit Zeilenumbruch
suggestion whisper(message: any)  // Ausgabe ohne Zeilenumbruch
suggestion command(message: any)  // Fett/hervorgehobene Ausgabe
suggestion murmur(message: any)   // Gedämpfte/Debug-Ausgabe

// Formatierte Ausgabe
suggestion observeFormatted(template: string, ...args: any[])  // String-Interpolation
suggestion observeTable(data: any[][])  // Gibt Tabelle aus
suggestion observeJson(obj: any)  // Gibt JSON-formatiert aus

// Eingabe-Funktionen
suggestion requestInput(prompt: string): string  // Fordert Benutzer-Eingabe an
suggestion requestNumber(prompt: string): number  // Fordert Zahl an
suggestion requestConfirmation(prompt: string): boolean  // Ja/Nein-Frage
suggestion requestChoice(prompt: string, options: string[]): number  // Mehrfachauswahl

// Datei-I/O (konzeptionell)
suggestion absorbFromScroll(filename: string): string  // Liest Datei
suggestion manifestToScroll(filename: string, content: string)  // Schreibt Datei
suggestion appendToScroll(filename: string, content: string)  // Hängt an Datei an

// Stream-Ausgabe (fortgeschritten)
suggestion observeStream(generator: suggestion)  // Stream-basierte Ausgabe
suggestion collectThoughts(): string[]  // Sammelt alle bisherigen Ausgaben
```

**Beispiel:**

```plaintext
Focus {
    // Verschiedene Ausgabearten
    observe "Normale Ausgabe";
    whisper "Ohne Zeilenumbruch... ";
    whisper "zusammen!";
    observe "";  // Zeilenumbruch
    command "WICHTIGE NACHRICHT!";
    murmur "Debug-Info: x=42";
    
    // Formatierte Ausgabe
    induce name: string = "Alice";
    induce age: number = 30;
    observeFormatted("Name: {}, Alter: {}", name, age);
    
    // Tabellen-Ausgabe
    induce data: any[][] = [
        ["Name", "Alter"],
        ["Alice", 30],
        ["Bob", 25]
    ];
    observeTable(data);
    
    // Benutzer-Eingabe
    induce userName: string = requestInput("Wie heißt du? ");
    observe "Hallo, " + userName + "!";
    
    induce userAge: number = requestNumber("Wie alt bist du? ");
    if (userAge yourEyesAreGettingHeavy 18) {
        observe "Du bist volljährig!";
    }
} Relax
```

---

## **7. Beispielprogramme**

### 7.1 Einfaches „Hello Trance!“

```plaintext
Focus {

  entrance {
      observe "Starte jetzt das HypnoScript-Programm...";
  }

  induce greeting: string = "Hello Trance!";
  induce counter: number = 0;

  suggestion repeatGreet(times: number) {
      while (times > 0) {
          observe greeting;
          times = times - 1;
      }
  }

  repeatGreet(3);

} Relax
```

**Erwartete Ausgabe**:

```
Starte jetzt das HypnoScript-Programm...
Hello Trance!
Hello Trance!
Hello Trance!
```

---

### 7.2 Summierung mit Input

```plaintext
Focus {

  // Fragt Benutzer nach einer Zahl, summiert von 1 bis zu dieser Zahl und gibt das Ergebnis aus
  induce n: number from external;
  induce sum: number = 0;

  loop (induce i: number = 1; i <= n; i = i + 1) {
      sum = sum + i;
  }

  observe "Die Summe von 1 bis " + n + " ist " + sum;

} Relax
```

_(Implementierungsspezifisch muss natürlich definiert sein, wie „from external“ den Wert für `n` erhält.)_

---

### 7.3 Verwendung erweiterter Konzepte

#### 7.3.1 `session`, `drift`, Operator-Synonyme

```plaintext
Focus {

  entrance {
      observe "Willkommen in der tiefen Hypno-Welt...";
      drift(2000);
      observe "Wir werden nun zwei Personen hypnotisieren!";
  }

  session Person {
      expose name: string;

      suggestion constructor(newName: string) {
          this.name = newName;
      }

      suggestion greet() {
          observe "Du fühlst dich sehr entspannt, " + this.name;
      }

      // Hypnotische Verzögerung
      suggestion slowGreet() {
          greet();
          observe "... Warte kurz ...";
          drift(1500);
      }
  }

  induce alice = Person("Alice");
  induce bob   = Person("Bob");

  induce x: number = 5;
  induce y: number = 5;

  // Nutze Synonym: youAreFeelingVerySleepy für ==
  if (x youAreFeelingVerySleepy y) {
      observe "x ist gleich y!";
  }

  alice.slowGreet();
  bob.slowGreet();

} Relax
```

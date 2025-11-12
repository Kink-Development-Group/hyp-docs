# **HypnoScript** – Eine esoterische, TypeScript-inspirierte Sprache mit hypnotischem Flair

> _"You are feeling very sleepy... Your code is getting deeper... and deeper..."_

---

## **Inhaltsverzeichnis**

- [**HypnoScript** – Eine esoterische, TypeScript-inspirierte Sprache mit hypnotischem Flair](#hypnoscript--eine-esoterische-typescript-inspirierte-sprache-mit-hypnotischem-flair)
  - [**Inhaltsverzeichnis**](#inhaltsverzeichnis)
  - [**1. Einleitung**](#1-einleitung)
    - [1.1 Philosophie](#11-philosophie)
    - [1.2 Design-Prinzipien](#12-design-prinzipien)
  - [**2. Grundaufbau**](#2-grundaufbau)
    - [2.1 Lexikalische Struktur](#21-lexikalische-struktur)
    - [2.2 Schlüsselwörter](#22-schlüsselwörter)
    - [2.3 Operatoren und Sonderzeichen](#23-operatoren-und-sonderzeichen)
    - [2.4 Bezeichner (Identifier)](#24-bezeichner-identifier)
    - [2.5 Literale](#25-literale)
    - [2.6 Typ-System und Annotationen](#26-typ-system-und-annotationen)
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
        - [Tafel der klassischen Suggestionen](#tafel-der-klassischen-suggestionen)
        - [Moderne Traum-Semantik](#moderne-traum-semantik)
      - [3.5.4 Benutzerdefinierte Strukturen/Typen: `tranceify`](#354-benutzerdefinierte-strukturentypen-tranceify)
      - [3.5.5 Muster-Entraining: `entrain`](#355-muster-entraining-entrain)
      - [3.5.6 Asynchrone Trance: `mesmerize` \& `await`](#356-asynchrone-trance-mesmerize--await)
      - [3.5.7 Module \& gemeinsame Trancen](#357-module--gemeinsame-trancen)
    - [Beispiel 1: Cleanup-Trigger](#beispiel-1-cleanup-trigger)
    - [Beispiel 2: Event-Handler für Wiederholungen](#beispiel-2-event-handler-für-wiederholungen)
    - [Beispiel 3: Parametrisierte Trigger](#beispiel-3-parametrisierte-trigger)
    - [Beispiel 4: Trigger in Sessions](#beispiel-4-trigger-in-sessions)
      - [3.5.9 Hypnotische Werkzeuge (Best-of)](#359-hypnotische-werkzeuge-best-of)
  - [**4. Grammatik (EBNF)**](#4-grammatik-ebnf)
  - [**5. Semantik**](#5-semantik)
    - [5.1 Variablen und Scope](#51-variablen-und-scope)
    - [5.2 Ein- / Ausgabe](#52-ein---ausgabe)
    - [5.3 Turing-Vollständigkeit](#53-turing-vollständigkeit)
    - [5.4 Fehlerbehandlung: Albtraum-Management](#54-fehlerbehandlung-albtraum-management)
    - [5.5 Parallelität und Trance-Synchronisation](#55-parallelität-und-trance-synchronisation)
  - [**6. Standardbibliothek**](#6-standardbibliothek)
    - [6.1 Tranceify-Bibliothek (Kernfunktionen)](#61-tranceify-bibliothek-kernfunktionen)
    - [6.2 Hypno-Math (Mathematische Funktionen)](#62-hypno-math-mathematische-funktionen)
    - [6.3 StringSpell (String-Manipulation)](#63-stringspell-string-manipulation)
    - [6.4 MemoryPalace (Datenstrukturen)](#64-memorypalace-datenstrukturen)
    - [6.5 TimeWarp (Zeit- und Datumsfunktionen)](#65-timewarp-zeit--und-datumsfunktionen)
    - [6.6 DeepMind (Erweiterte Kontrollstrukturen)](#66-deepmind-erweiterte-kontrollstrukturen)
    - [6.7 SensoryInput (Ein-/Ausgabe-Funktionen)](#67-sensoryinput-ein-ausgabe-funktionen)
    - [6.8 AuraAsync (Asynchronität \& Tasks)](#68-auraasync-asynchronität--tasks)
    - [6.9 DreamWeaver Patterns (Pattern Matching)](#69-dreamweaver-patterns-pattern-matching)
    - [6.10 Stagecraft Visions (UI \& Präsentation)](#610-stagecraft-visions-ui--präsentation)
    - [6.11 HypnoNet (Netzwerk \& APIs)](#611-hypnonet-netzwerk--apis)
    - [6.12 RealityAnchor (Persistenz \& Storage)](#612-realityanchor-persistenz--storage)
    - [6.13 LucidDiagnostics (Debugging \& Telemetrie)](#613-luciddiagnostics-debugging--telemetrie)
  - [**7. Beispielprogramme**](#7-beispielprogramme)
    - [7.1 Einfaches „Hello Trance!“](#71-einfaches-hello-trance)
    - [7.2 Summierung mit Input](#72-summierung-mit-input)
    - [7.3 Verwendung erweiterter Konzepte](#73-verwendung-erweiterter-konzepte)
      - [7.3.1 `session`, `drift`, Operator-Synonyme](#731-session-drift-operator-synonyme)

---

## **1. Einleitung**

**HypnoScript** ist eine moderne, esoterische Programmiersprache, die sich an die Syntax von TypeScript/JavaScript anlehnt und dabei konsequent Klischees und Metaphern aus der Welt der Hypnose verwendet. Die Sprache vereint humorvolle Themenwahl mit ernsthafter Funktionalität und bietet ein vollständiges, Turing-vollständiges Sprachsystem.

### 1.1 Philosophie

HypnoScript folgt dem Paradigma der **"Hypnotischen Programmierung"**, bei der:

- **Code als Suggestion** betrachtet wird – Programme sind Sequenzen von Suggestionen an den Computer
- **Variablen in Trance versetzt** werden – Werte werden induziert, implantiert oder eingebettet
- **Kontrollfluss als Trance-Tiefe** metaphorisiert wird – tiefere Verschachtelung = tiefere Trance
- **Funktionen als hypnotische Suggestions** wirken – sie beeinflussen den Zustand des Programms
- **Fehler als "Erwachen aus der Trance"** behandelt werden – unerwartete Zustände durchbrechen den Flow

### 1.2 Design-Prinzipien

1. **Konsistenz**: Alle Sprachelemente folgen der hypnotischen Metapher
2. **Lesbarkeit**: Trotz esoterischer Begriffe bleibt die Struktur vertraut
3. **Modernität**: Unterstützung für Pattern Matching, Async/Await, Type Safety
4. **Vollständigkeit**: Umfangreiche Standardbibliothek für praktische Anwendungen
5. **Spaß**: Die Sprache soll zum Experimentieren einladen und unterhalten

**Kerneigenschaften:**

- Turing-vollständig
- Statisches Typsystem mit Typ-Inferenz
- Objektorientierung mit Session-Konzept
- Funktionale Programmierung (First-Class Functions, Closures, Lambda)
- Pattern Matching
- Async/Await für asynchrone Operationen
- Umfassende Standardbibliothek
- Module-System für Code-Organisation

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
entrance, finale,
if, else, when, otherwise,
while, loop, pendulum,
snap, sink, sinkTo,
suggestion, mesmerize, awaken, await, surrenderTo, call,
entrain,
induce, implant, embed, freeze, sharedTrance,
observe, whisper, command, murmur,
mindLink, from, external,
session, constructor,
expose, conceal, dominant,
tranceify, anchor, trigger, oscillate,
drift, suspend, pauseReality, accelerateTime, decelerateTime,
deepFocus, deeperStill,
trance, subconscious, lucid,
number, string, boolean,
true, false,
youAreFeelingVerySleepy, lookAtTheWatch, fallUnderMySpell,
youCannotResist, yourEyesAreGettingHeavy, goingDeeper,
underMyControl, resistanceIsFutile, lucidFallback, dreamReach
```

> Hinweis: Zusätzliche hypnotische Begriffe findest du in Kapitel „Erweiterte Konzepte“.

### 2.3 Operatoren und Sonderzeichen

- **Zuweisung**: `=`
- **Arithmetisch**: `+`, `-`, `*`, `/`, `%`
- **Vergleich**: `==`, `!=`, `>`, `>=`, `<`, `<=` (ergänzt durch hypnotische Synonyme, siehe [3.5.3](#353-hypnotische-operator-synonyme))
- **Logisch**: `&&`, `||`, `!`
- **Nullish/Optional**: `??`, `?.` (alias `lucidFallback`, `dreamReach`)
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

> Hinweis: Der Fantasietyp `trance` besitzt keine Literale, eignet sich aber als Typannotation.

### 2.6 Typ-System und Annotationen

HypnoScript residiert in einer statisch getypten, aber äußerst suggestiven Traumwelt. Jede Variable kann – muss aber nicht – einen sichtbaren Typ tragen. Fehlt die Annotation, induziert der Interpreter den Typ via Trance-Intuition.

- **Basistypen**: `number`, `string`, `boolean`, `trance` (für bewusstseinserweiterte Payloads).
- **Modifier**: `lucid` markiert Werte als optional/entrückt (`lucid string` ≙ `string | null | undefined`).
- **Kombinationen**: Union (`typeA | typeB`) und Intersection (`typeA & typeB`) werden unterstützt – passend zu verschmelzenden Trancezuständen.
- **Generics**: Funktionen, Sessions und `tranceify`-Typen können Typparameter verwenden (`suggestion anchor<T>(value: T): T`).
- **Optionale Felder**: Das Suffix `?` auf einem Feld/einer Signatur kennzeichnet „sanft mögliche“ Werte.
- **Nullish-Handling**: Der Operator `lucidFallback` (Alias für `??`) und `dreamReach` (Alias für `?.`) helfen, schlafwandelnde Werte sicher zu berühren.

```plaintext
induce guestCount: number = 42;
induce mantra: lucid string;           // optionaler Wert
induce guestRegistry = { entries: [] };

tranceify HypnoGuest<TMemory> {
    name: string;
    memory: TMemory;
    isInTrance: boolean;
    suggestionLevel?: number;
}

suggestion summonEcho<T>(value: T | trance, fallback: T): T {
    awaken value lucidFallback fallback;
}

observe guestRegistry dreamReach entries lucidFallback [];
```

> Hinweis: `lucidFallback` (`??`) und `dreamReach` (`?.`) sind syntaktischer Zucker für Nullish-Coalescing und Optional-Chaining – passend ins hypnotische Bühnenbild übersetzt.

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
- **Modifiers**: `mesmerize suggestion` erzeugt asynchrone Funktionen, `imperative suggestion` kennzeichnet Prozeduren, `dominant suggestion` statische/bibliothekarische Hooks.

> Hinweis: Für Funktionen ohne Rückgabewert kann man wahlweise `imperative suggestion` verwenden (siehe [3.5](#35-erweiterte-konzepte)).

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

> Hinweis: Die konkrete Warte-Strategie hängt von Interpreter oder Runtime ab.

#### 3.5.3 Hypnotische Operator-Synonyme

Wo andere Sprachen nüchtern vergleichen, flüstert HypnoScript beschwörende Formeln. Jede Vergleichs- und Logikoperation besitzt ein theatrales Alias, das exakt dieselbe Semantik behält – nur viel mehr Show liefert.

##### Tafel der klassischen Suggestionen

| Standard-Operator | Hypnotisches Synonym      | Bedeutung           |
| ----------------- | ------------------------- | ------------------- |
| `==`              | `youAreFeelingVerySleepy` | Gleichheit          |
| `!=`              | `youCannotResist`         | Ungleichheit        |
| `>`               | `lookAtTheWatch`          | Größer als          |
| `<`               | `fallUnderMySpell`        | Kleiner als         |
| `>=`              | `yourEyesAreGettingHeavy` | Größer oder gleich  |
| `<=`              | `goingDeeper`             | Kleiner oder gleich |
| `&&`              | `underMyControl`          | Logisches UND       |
| `\|\|`            | `resistanceIsFutile`      | Logisches ODER      |

##### Moderne Traum-Semantik

| Konstruktion | Hypnotisches Synonym | Wirkung                        |
| ------------ | -------------------- | ------------------------------ |
| `??`         | `lucidFallback`      | Nullish-Coalescing             |
| `?.`         | `dreamReach`         | Optional-Chaining auf Objekten |
| `?.[`        | `dreamReach[`        | Optionaler Indexzugriff        |
| `?.(`        | `dreamReach(`        | Optionaler Funktionsaufruf     |

Die Synonyme können frei mit den Standardoperatoren gemischt werden. Für konsistente Hypnose empfiehlt es sich, pro Datei einen Stil zu wählen.

```plaintext
induce age: number = 22;
induce license: boolean = true;
if (age lookAtTheWatch 18 underMyControl license youAreFeelingVerySleepy true) {
    observe "Du darfst fahren!";
}

induce guest = { profile: { alias: "Hypna" } };
induce dossier = guest dreamReach profile lucidFallback {};
observe dossier;

induce x: number = 7;
induce y: number = 42;
if (x goingDeeper 100 resistanceIsFutile y yourEyesAreGettingHeavy 50) {
    command "Bedingung erfüllt – trance tiefer!";
}

induce password: string = "secret";
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

#### 3.5.5 Muster-Entraining: `entrain`

`entrain` ist HypnoScripts Pattern-Matching und wirkt wie ein sanftes Einschwingen auf unterschiedliche Bewusstseinslagen. Der Ausdruck wird einmal evaluiert, anschließend werden die `when`-Klauseln der Reihe nach geprüft. Die erste passende Suggestion gewinnt; `otherwise` dient als Fallback.

- Literale (`when 0`, `when "Spirale"`).
- Typ-Patterns mit optionaler Bindung (`when value: number`).
- Destrukturierung von `tranceify`-Records und Arrays (`when HypnoGuest { name, isInTrance: true }`).
- Guards mit `if` für zusätzliche Bedingungen.
- Spread-Operator `...rest` innerhalb von Array-Pattern.

```plaintext
induce input: any = HypnoGuest<{ tranceDepth: number }> {
    name: "Luna",
    memory: { tranceDepth: 7 },
    isInTrance: true,
    suggestionLevel: 5,
};

entrain input {
    when 0 => command "Nullpunkt erreicht.";
    when value: number if value lookAtTheWatch 0 => command "Positive Schwingung!";
    when HypnoGuest { name, isInTrance: true } => observe name + " ist tief in Trance.";
    when [first, ...rest] => observe "Liste startet mit " + first;
    otherwise => observe "Unbekannter Bewusstseinszustand";
}
```

Jede `when`-Klausel kann `awaken` verwenden, um einen Wert zurückzugeben. `entrain` selbst ist also ein Ausdruck und lässt sich direkt einer Variable zuweisen.

#### 3.5.6 Asynchrone Trance: `mesmerize` & `await`

Für Operationen, die im Hintergrund schweben, markiert `mesmerize` eine Funktion als hypnotisch-asynchron. Der Rückgabewert entspricht einem Promise; `await` (alias `surrenderTo`) löst die Suggestion auf.

```plaintext
mesmerize suggestion lullaby(): number {
    drift(1200);
    awaken 42;
}

Focus {
    induce answer: number = await lullaby();
    observe "Antwort aus dem Traum: " + answer;

    induce secondAnswer: number = surrenderTo lullaby();
    observe "Alias funktioniert ebenso.";
} Relax
```

`mesmerize` kann mit `session` kombiniert werden, um hypnotische Services zu definieren. Innerhalb von `mesmerize`-Funktionen stehen `parallelTrance` und `scheduleAwakening` aus der Standardbibliothek zur Verfügung.

#### 3.5.7 Module & gemeinsame Trancen

Das Modul-System bildet die Bühne, auf der mehrere Skripte gemeinsam schwingen.

```plaintext
mindLink "./rituals/spiral.hyp";
mindLink { chant as deepChant } from "./choir.hyp";

sharedTrance freeze stageLighting: string = "violett";
sharedTrance induce visitorCount: number = 0;

imperative suggestion incrementVisitors() {
    visitorCount = visitorCount + 1;
    deepChant();
}
```

- `mindLink` lädt Module; benannte Importe funktionieren wie in modernen JS-Ökosystemen.
- `sharedTrance` deklariert modulweite Zustände (ggf. mit `freeze`).
- `manifest` (optional) kann verwendet werden, um Assets zu exportieren (Implementierungsdetail des Toolings).

`trigger` ist ein mächtiges Werkzeug zum Definieren von Event-Hooks, Callbacks und verzögerten Aktionen. Ein Trigger bindet eine Funktions-Expression an einen Bezeichner und kann später explizit aufgerufen oder als Reaktion auf bestimmte Ereignisse ausgelöst werden.

**Syntax:**

```plaintext
trigger triggerName = suggestion(parameterList) {
    // Trigger-Code
};
```

**Eigenschaften:**

- **Deklarativ**: Triggers werden wie Variablen deklariert, binden aber Funktionslogik
- **First-Class**: Können als Parameter übergeben, in Datenstrukturen gespeichert und dynamisch aufgerufen werden
- **Event-Orientiert**: Ideal für Event-Handler, Callbacks, Cleanup-Aktionen und verzögerte Ausführungen
- **Kombination mit Bibliotheken**: Perfekt mit `repeatAction`, `delayedSuggestion`, `awakenAfter` aus DeepMind/AuraAsync

**Verwendungsmuster:**

1. **Cleanup-Trigger**: Aufräumaktionen nach Programmende (oft in `finale`-Blöcken)
2. **Event-Handler**: Reaktion auf Benutzer-Interaktionen oder Systemereignisse
3. **Callback-Funktionen**: Als Parameter für höhere Funktionen (DeepMind, MemoryPalace)
4. **State-Management**: Zustandsänderungs-Handler in komplexen Sessions

### Beispiel 1: Cleanup-Trigger

```plaintext
Focus {
    induce resourceHandle: number = 42;

    trigger onCleanup = suggestion() {
        command "Ressourcen werden freigegeben...";
        resourceHandle = 0;
        observe "Cleanup abgeschlossen.";
    };

    // Programm-Logik...
    observe "Hauptprogramm läuft...";

    finale {
        onCleanup();  // Expliziter Aufruf des Triggers
    }
} Relax
```

### Beispiel 2: Event-Handler für Wiederholungen

```plaintext
Focus {
    induce counter: number = 0;

    trigger onTick = suggestion() {
        counter = counter + 1;
        observe "Tick " + counter;
    };

    // Verwende Trigger mit DeepMind
    repeatAction(5, onTick);

    observe "Finale Zählung: " + counter;
} Relax
```

### Beispiel 3: Parametrisierte Trigger

```plaintext
Focus {
    trigger onError = suggestion(errorCode: number, message: string) {
        command "⚠️ FEHLER " + errorCode + ": " + message;
        drift(1000);
    };

    induce x: number = 10;
    if (x lookAtTheWatch 100) {
        onError(404, "Wert zu groß!");
    }
} Relax
```

### Beispiel 4: Trigger in Sessions

```plaintext
session HypnoTimer {
    expose elapsedSeconds: number;
    conceal tickTrigger: trigger;

    suggestion constructor() {
        this.elapsedSeconds = 0;
        this.tickTrigger = trigger onSecondElapsed = suggestion() {
            this.elapsedSeconds = this.elapsedSeconds + 1;
            observe "Verstrichene Zeit: " + this.elapsedSeconds + "s";
        };
    }

    suggestion start() {
        repeatAction(10, this.tickTrigger);
    }
}

Focus {
    induce timer = HypnoTimer();
    timer.start();
} Relax
```

**Unterschied zu normalen Funktionen:**

| Aspekt      | `suggestion`                            | `trigger`                                   |
| ----------- | --------------------------------------- | ------------------------------------------- |
| Deklaration | `suggestion name(params): type { ... }` | `trigger name = suggestion(params) { ... }` |
| Semantik    | Wiederverwendbare Funktion              | Event-Handler/Callback                      |
| Verwendung  | Allgemeine Logik                        | Ereignisgesteuert                           |
| Konvention  | Algorithmen, Berechnungen               | Reaktionen, Cleanup, Events                 |

**Best Practices:**

- Verwende `trigger` für Event-Handler und Callbacks
- Benenne Triggers mit Präfix `on` für Klarheit (`onAwaken`, `onError`, `onComplete`)
- Kombiniere mit `finale`-Blöcken für garantierte Ausführung
- Nutze Triggers in Kombination mit DeepMind-Funktionen für elegante Kontrollflüsse

> Hinweis: Trigger sind syntaktischer Zucker für Funktions-Expressions mit event-orientierter Semantik. Intern werden sie als First-Class Functions behandelt.

#### 3.5.9 Hypnotische Werkzeuge (Best-of)

Eine Auswahl weiterer Sprachjuwelen, die den Hypnose-Charakter abrunden:

- `imperative suggestion`: Prozedur ohne Rückgabewert.
- `anchor` & `deepenTrance`: Zustand sichern bzw. Trance-Level erhöhen.
- `oscillate`, `pendulum`: Toggler und bidirektionale Schleifen.
- `suspend`: Pausiert ohne festes Ende, bis ein Trigger aufweckt.
- `freeze`: Macht Variablen unveränderlich.
- `whisper`, `command`, `murmur`: Ausgabestufen vom Flüstern bis zur Autorität.
- `implant`/`embed`: Alternativen zu `induce` für tiefere Speicheroperationen.
- `subconscious`: Zugriff auf verborgene Speicherbereiche.
- `sinkTo label;`: Goto-artiger Sprung für dramatische Effekte – möglichst sparsam einsetzen.
- `finale { ... }`: Aufräum- und Abschlussblock nach dem Hauptprogramm.

> Siehe auch [3.5.8 Trigger](#358-trigger-event-hooks--callback-mechanismen) für vollständige Event-Hook-Dokumentation.

```plaintext
sharedTrance freeze mantraText: string = "Atme ein, atme aus";

Focus {
    anchor baselineDepth = 3;
    induce isDeepening: boolean = false;

    oscillate isDeepening;
    if (isDeepening) {
        observe "Trance wird vertieft auf Level: " + baselineDepth;
    }

    pendulum (induce i: number = 0; i fallUnderMySpell 3) {
        whisper mantraText + " (" + i + ")";
        drift(300);
    }

    trigger onAwaken = suggestion() {
        command "Du bist wieder ganz da.";
    };

    // Nostalgischer Sprung, bitte nur im Ausnahmefall:
    myLabel:
    baselineDepth = baselineDepth - 1;
    if (baselineDepth fallUnderMySpell 1) sinkTo myLabel;

    finale {
        onAwaken();
    }
} Relax
```

> Hinweis: Viele dieser Features sind Zuckerguss. Für produktive Hypnose gilt – dosiert einsetzen, damit niemand aus der Trance fällt.

---

## **4. Grammatik (EBNF)**

Nachfolgend eine beispielhafte EBNF-Skizze, die die Kernsyntax (ohne alle Operator-Synonyme) abbildet. Die Synonyme (`youAreFeelingVerySleepy`, etc.) könnten in der Praxis direkt auf die Standardoperatoren gemappt werden.

```ebnf
Program          ::= "Focus" Block [ FinaleBlock ] "Relax" ;

Block            ::= { Statement } ;

Statement        ::= VarDeclarationStatement
                   | SharedTranceDeclaration
                   | FreezeStatement
                   | MindLinkStatement
                   | EntrainStatement
                   | IfStatement
                   | WhileStatement
                   | LoopStatement
                   | PendulumStatement
                   | BreakStatement
                   | ContinueStatement
                   | FunctionDeclaration
                   | TriggerDeclaration
                   | ReturnStatement
                   | ObserveStatement
                   | WhisperStatement
                   | CommandStatement
                   | DriftStatement
                   | AnchorStatement
                   | OscillateStatement
                   | SessionDeclaration
                   | TranceifyDeclaration
                   | EntranceBlock
                   | FinaleBlock
                   | LabelStatement
                   | SinkToStatement
                   | BlockStatement
                   | ExpressionStatement ;

BlockStatement   ::= [ "deepFocus" | "deeperStill" ] "{" { Statement } "}" ;

EntranceBlock    ::= "entrance" BlockStatement ;
FinaleBlock      ::= "finale" BlockStatement ;

VarDeclarationStatement
                   ::= ("induce" | "implant" | "embed") Identifier [ ":" Type ] [ "=" Expression ] ";"
                   | ("induce" | "implant") Identifier [ ":" Type ] "from" "external" ";" ;

SharedTranceDeclaration
                   ::= "sharedTrance" ("freeze" | "induce" | "implant" | "embed")
                       Identifier [ ":" Type ] [ "=" Expression ] ";" ;

FreezeStatement  ::= "freeze" Identifier ":" Type "=" Expression ";" ;

MindLinkStatement
                   ::= "mindLink" StringLiteral [ "as" Identifier ] ";"
                   | "mindLink" "{" ImportList "}" "from" StringLiteral ";" ;

ImportList       ::= ImportSpecifier { "," ImportSpecifier } ;
ImportSpecifier  ::= Identifier [ "as" Identifier ] ;

ObserveStatement ::= "observe" Expression ";" ;
WhisperStatement ::= "whisper" Expression ";" ;
CommandStatement ::= "command" Expression ";" ;

DriftStatement   ::= ("drift" | "pauseReality") "(" Expression ")" ";" 
                   | "suspend" ";" ;

AnchorStatement  ::= "anchor" Identifier "=" Expression ";" ;
OscillateStatement ::= "oscillate" Identifier ";" ;

LabelStatement   ::= Identifier ":" ;
SinkToStatement  ::= "sinkTo" Identifier ";" ;

PendulumStatement
                   ::= "pendulum" "(" [ VarDeclarationStatementNoSemicolon ]
                                    ";" Expression ";" Expression ")"
                       BlockStatement ;

IfStatement      ::= "if" "(" Expression ")" BlockStatement [ "else" BlockStatement ] ;
WhileStatement   ::= "while" "(" Expression ")" BlockStatement ;
LoopStatement    ::= "loop" "(" [ VarDeclarationStatementNoSemicolon ]
                                ";" Expression ";" Expression ")" BlockStatement ;

BreakStatement   ::= "snap" ";" ;
ContinueStatement::= "sink" ";" ;

FunctionDeclaration
                   ::= FunctionModifier Identifier "(" [ ParameterList ] ")" [ ":" Type ]
                       BlockStatement ;

FunctionModifier ::= [ "mesmerize" ] ( "suggestion"
                                      | "imperative suggestion"
                                      | "dominant suggestion" ) ;

TriggerDeclaration
                   ::= "trigger" Identifier "=" FunctionExpression ";" ;

FunctionExpression
                   ::= [ "mesmerize" ] "suggestion" "(" [ ParameterList ] ")"
                       BlockStatement ;

ParameterList    ::= Parameter { "," Parameter } ;
Parameter        ::= Identifier [ ":" Type ] ;

ReturnStatement  ::= "awaken" [ Expression ] ";" ;

ExpressionStatement
                   ::= Expression ";" ;

Expression       ::= AssignmentExpression ;

AssignmentExpression
                   ::= LogicalOrExpression [ "=" AssignmentExpression ] ;

LogicalOrExpression
                   ::= LogicalAndExpression { ( "||" | "resistanceIsFutile" ) LogicalAndExpression } ;

LogicalAndExpression
                   ::= EqualityExpression { ( "&&" | "underMyControl" ) EqualityExpression } ;

EqualityExpression
                   ::= RelationalExpression { EqualityOperator RelationalExpression } ;

EqualityOperator ::= "==" | "!=" | "youAreFeelingVerySleepy" | "youCannotResist" ;

RelationalExpression
                   ::= AdditiveExpression { RelationalOperator AdditiveExpression } ;

RelationalOperator
                   ::= ">" | ">=" | "<" | "<="
                    | "lookAtTheWatch" | "yourEyesAreGettingHeavy"
                    | "fallUnderMySpell" | "goingDeeper" ;

AdditiveExpression
                   ::= MultiplicativeExpression { ( "+" | "-" ) MultiplicativeExpression } ;

MultiplicativeExpression
                   ::= UnaryExpression { ( "*" | "/" | "%" ) UnaryExpression } ;

UnaryExpression  ::= ( "await" | "surrenderTo" ) UnaryExpression
                   | [ ("+" | "-" | "!") ] PrimaryExpression ;

PrimaryExpression
                   ::= Identifier
                   | Literal
                   | "(" Expression ")"
                   | FunctionCall
                   | FunctionExpression
                   | EntrainExpression ;

FunctionCall     ::= [ "call" ] Identifier "(" [ ArgumentList ] ")" ;

EntrainExpression
                   ::= "entrain" Expression "{" EntrainClause { EntrainClause } [ EntrainDefault ] "}" ;

EntrainStatement ::= EntrainExpression ";" ;

EntrainClause    ::= "when" Pattern [ "if" Expression ] "=>" BlockStatement ;
EntrainDefault   ::= "otherwise" "=>" BlockStatement ;

Pattern          ::= Literal
                   | Identifier
                   | Identifier ":" Type
                   | Identifier "{" RecordPatternEntry { "," RecordPatternEntry } "}"
                   | "[" [ Pattern { "," Pattern } [ "," "..." Identifier ] ] "]" ;

RecordPatternEntry ::= Identifier [ ":" Pattern ] [ "=" Expression ] ;

ArgumentList     ::= Expression { "," Expression } ;

SessionDeclaration
                   ::= "session" Identifier "{" { SessionMember } "}" ;

SessionMember    ::= ( "expose" | "conceal" )?
                       ( VarDeclarationStatementNoSemicolon
                       | FunctionDeclaration
                       | ConstructorDeclaration ) ;

ConstructorDeclaration
                   ::= "suggestion" "constructor" "(" [ ParameterList ] ")" BlockStatement ;

TranceifyDeclaration
                   ::= "tranceify" Identifier "{" { VarDefinition } "}" ;

VarDefinition    ::= Identifier ":" Type ";" ;

VarDeclarationStatementNoSemicolon
                   ::= ("induce" | "implant" | "embed") Identifier [ ":" Type ] [ "=" Expression ]
                   | ("induce" | "implant") Identifier [ ":" Type ] "from" "external" ;

Literal          ::= NumericLiteral | StringLiteral | BooleanLiteral ;
NumericLiteral   ::= Digit { Digit } [ "." Digit { Digit } ] ;
StringLiteral    ::= '"' { <char außer '"' oder Zeilenumbruch> } '"' ;
BooleanLiteral   ::= "true" | "false" ;

Type             ::= "number" | "string" | "boolean" | "trance" | Identifier ;

Digit            ::= [0-9] ;
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

### 5.4 Fehlerbehandlung: Albtraum-Management

HypnoScript kennt Ausnahmen als **Nightmares**. Sobald ein Nightmare ausgelöst wird, bricht die aktuelle Suggestion ab, bis eine passende Recovery-Suggestion eingreift.

- `tryOrAwaken(action, recovery)`: Führt `action` aus und ruft bei Nightmare `recovery` auf.
- `ensureAwakening(action, cleanup)`: Stellt sicher, dass `cleanup` ausgeführt wird (ähnlich `finally`).
- `lucidFallback`: Ausdrucksebene für Nullish- bzw. Fehler-Ersatzwerte.
- `dreamReach`: Optional-Chaining schützt vor `subconscious`-Nullzuständen.

```plaintext
tryOrAwaken(
    suggestion() {
        surrenderTo fetchSuggestion("https://hypno.api/session");
    },
    suggestion(nightmare: Nightmare) {
        murmur "Albtraum: " + nightmare.message;
        observe "Wir atmen tief durch und versuchen es erneut.";
    }
);

ensureAwakening(
    suggestion() { openVault(); },
    suggestion() { closeVault(); }
);
```

### 5.5 Parallelität und Trance-Synchronisation

Asynchrone Suggestionen (`mesmerize`, `await`) und die Bibliotheken AuraAsync sowie DeepMind ermöglichen nebeneinander laufende Hypnosen.

- `parallelTrance` startet mehrere Suggestionen gleichzeitig und wartet auf Abschluss.
- `sequentialTrance` erzwingt Reihenfolge, nützlich beim Aktualisieren von `sharedTrance`-Zuständen.
- `auraToken` / `cancelSuggestion` erlauben Abbrüche.
- `sharedTrance`-Variablen sind per Definition threadsicher; für kritische Abschnitte kann `anchor` + `oscillate` zur Koordination genutzt werden.

```plaintext
Focus {
    sharedTrance induce stage: string = "warmup";

    parallelTrance([
        suggestion() { stage = "intro"; surrenderTo lullaby(); },
        suggestion() { observe "Publikum zählt rückwärts"; }
    ]);

    sequentialTrance([
        suggestion() { stage = "climax"; },
        suggestion() { command "3...2...1..."; }
    ]);
} Relax
```

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
    observe "Anzahl Wörter: " + vaultSize(words);

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
suggestion addSeconds(timestamp: number, seconds: number): number
suggestion differenceInDays(ts1: number, ts2: number): number
suggestion differenceInHours(ts1: number, ts2: number): number
suggestion differenceInMinutes(ts1: number, ts2: number): number
suggestion differenceInSeconds(ts1: number, ts2: number): number

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

### 6.8 AuraAsync (Asynchronität & Tasks)

AuraAsync orchestriert hypnotische Hintergrundprozesse und liefert Kontrollstrukturen für komplexe Aufgabenketten.

```plaintext
mesmerize suggestion lull(ms: number): trance              // Resolves nach Ablauf der Zeit
mesmerize suggestion awakenAfter(ms: number, action: suggestion)  // Verzögert Aktion, liefert AuraToken
mesmerize suggestion mesmerizeAll(actions: suggestion[]): trance[]  // Wartet auf alle Suggestions
mesmerize suggestion tranceRace(actions: suggestion[]): any         // Liefert erstes Ergebnis
suggestion auraToken(): AuraToken                          // Erzeugt Abbruch-Token
suggestion cancelSuggestion(token: AuraToken)              // Bricht geplante Aktion ab
```

**Beispiel:**

```plaintext
mesmerize suggestion stageEntry() {
    observe "Vorhang zu";
    await lull(1500);
    command "Vorhang auf!";
}

Focus {
    induce token = surrenderTo awakenAfter(5000, suggestion() { command "Applaus"; });
    surrenderTo stageEntry();
    cancelSuggestion(token);  // optionaler Abbruch
} Relax
```

> Hinweis: `AuraToken` ist eine von AuraAsync bereitgestellte `tranceify`-Struktur für Cancel-Operationen.

### 6.9 DreamWeaver Patterns (Pattern Matching)

DreamWeaver ergänzt `entrain` um Hilfsfunktionen, um Muster deklarativ zu beschreiben und zu validieren.

```plaintext
suggestion weave(target: any, pattern: PatternDefinition): boolean
suggestion captureBindings(target: any, pattern: PatternDefinition): MemoryMap
suggestion guardWith(target: any, predicate: suggestion): boolean
suggestion compileSigil(pattern: string): PatternDefinition
suggestion matchMany(values: any[], pattern: PatternDefinition): any[]
```

Die Bibliothek erlaubt es, häufig genutzte Muster als wiederverwendbare Sigille zu hinterlegen und sorgt für ein konsistentes Bindungs-Layout in komplexen `entrain`-Konstrukten.

> Hinweis: `PatternDefinition` ist ein `tranceify`-Record, der Pattern-Strukturen, Guards und Metadaten bündelt.

### 6.10 Stagecraft Visions (UI & Präsentation)

Stagecraft Visions steuert visuelle und auditive Effekte für Bühnen-Hypnosen, Dashboards oder CLI-Inszenierungen.

```plaintext
suggestion renderSpiral(frames: number)                    // ASCII-/Canvas-Spirale erzeugen
suggestion projectAura(message: string, style?: StageStyle) // Gestylte Ausgabe
suggestion dimLights(level: number)                         // Farben/Helligkeit anpassen
suggestion cueSoundtrack(track: string)                     // Hintergrundmusik triggern
suggestion presentTimeline(events: any[]): void             // Timeline/Step-Visualizer rendern
```

### 6.11 HypnoNet (Netzwerk & APIs)

HypnoNet verbindet HypnoScript mit externen Diensten, APIs und Webhooks.

```plaintext
mesmerize suggestion fetchSuggestion(url: string, options?: NetOptions): trance
mesmerize suggestion postSuggestion(url: string, payload: any, options?: NetOptions): trance
mesmerize suggestion openMindStream(url: string, onChunk: suggestion): AuraToken
suggestion encodeMindLink(payload: any): string
suggestion decodeMindLink(serialized: string): any
```

### 6.12 RealityAnchor (Persistenz & Storage)

RealityAnchor verwaltet dauerhafte Ankerpunkte – Dateien, Datenbanken oder In-Memory-Vaults.

```plaintext
suggestion storeMemory(anchor: string, value: any)
suggestion recallMemory(anchor: string): any
suggestion forgetMemory(anchor: string)
suggestion listAnchors(): string[]
mesmerize suggestion syncVault(path: string): void
```

### 6.13 LucidDiagnostics (Debugging & Telemetrie)

LucidDiagnostics unterstützt beim Messen, Protokollieren und Visualisieren von Trance-Zuständen.

```plaintext
suggestion startTracer(label: string): TraceHandle
suggestion recordLucidity(message: string)
suggestion probeDepth(action: suggestion): number
suggestion captureDreamDump(): string
suggestion withHypnoTimer(label: string, action: suggestion): number
```

> Hinweis: `TraceHandle` kapselt interne Timer- und Context-Daten und kann mit `captureDreamDump` serialisiert werden.

**Szenario:** HypnoNet kombiniert mit DreamWeaver Patterns lässt sich verwenden, um externe Daten zu holen, via `entrain` zu analysieren und anschließend auf der Bühne mit Stagecraft glamourös aufzubereiten.

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

```plaintext
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

> Hinweis: Implementierungen müssen definieren, wie `from external` den Wert für `n` bezieht.

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

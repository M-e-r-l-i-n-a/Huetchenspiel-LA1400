# Portfolioeintrag zum Hütchenspiel
Dieses Programm ist im Lernatelier entstanden, einem Fach in der Informatikmittelschule, in dem wir eigene Projekte programmieren dürfen. Unsere Vierergruppe hat mit C# WinForms ein Programm geschrieben, bei dem der Nutzer das Hütchen erraten soll, unter dem das gesetzte Geld versteckt ist.

### Ziele:
1. Ich möchte erklären, wie man ein neues Form öffnet, wenn man ein anderes geschlossen hat.
2. Ich möchte ein Anwendungsbeispiel zeigen.

### Erklärung:
Wenn man einen Button drückt, kann man das als Signal benutzen, das aktuelle Form zu schliessen, um ein neues zu öffnen. Dazu muss man eine Funktion erstellen mit `button1_Click`, wobei die Zahl natürlich variieren kann. Um das neue Form zu öffnen, muss man zuerst eine Variable daraus machen, mit `Form2 game = new Form2()`. In die Klammern kann man Variablen einfügen, die man übergeben möchte. Anschliessend kann man schreiben `game.Show()` und das neue Fenster wird geöffnet. Um das alte Fenster zu schliessen, kann man einfach `this.Hide()` verwenden.

### Anwendungsbeispiel:
### Code:

``` c#
private void button1_Click(object sender, EventArgs e)
        {
            Form2 game = new Form2(money, upgradelist);
            game.Show();
            this.Hide();
        }
```

#### Video unseres Projekts:
[![Video des Beispiels](https://img.youtube.com/vi/COJL3pRsVeY/0.jpg)](http://www.youtube.com/watch?v=COJL3pRsVeY "Video des Beispiels - Klicke um es anzuschauen!")

### Verifikation:
Ziel 1 habe ich im Abschnitt *Erklärung* erreicht und Ziel 2 im Abschnitt *Anwendungsbeispiel* (*Code* und *Video*).

### Reflexion:
Die Gruppenarbeit fand ich schwierig, weil zwei aus einer anderen Klasse waren und wir nicht so viel miteinander gesprochen haben. Wie auch letztes Mal versuche ich, nächstes Mal mehr auf andere zuzugehen und mit ihnen zu sprechen.

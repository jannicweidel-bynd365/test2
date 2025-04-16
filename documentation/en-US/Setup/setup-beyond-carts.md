---
title: "Beyond Carts einrichten"
author: jannicweidel-bynd365
ms.author: jannicweidel-bynd365
ms.custom: na
ms.date: 20/11/2023
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-service: ""
---

# <a name="setup-beyond-carts"></a>Beyond Carts einrichten

In diesem Kapitel wird beschrieben, wie Sie Beyond Carts einrichten.  
Beachten Sie, dass Ihnen der entsprechende Berechtigungssatz für die Einrichtung von Beyond Carts zugewiesen ist. Weitere Informationen darüber, wie der 
Berechtigungssatz zugeordnet wird, erhalten Sie unter dem Kapitel [Benutzerberechtigungen zuweisen](assign-permission-set.md).  

Um Beyond Carts einzurichten, gehen Sie wie folgt vor:  

1. Rufen Sie aus dem Rollencenter die Suchfunktion auf (**ALT+Q**).  
1. Suchen Sie nach **[Beyond Carts Einrichtung](https://businesscentral.dynamics.com/?page=70838780)** und klicken Sie auf das entsprechende Suchergebnis.  
1. Die Seite **Beyond Carts Einrichtung** wird angezeigt.  
   ![beyond-carts-setup](../assets/beyond-carts-setup.png)  
1. Öffnen Sie die Dropdownliste für das Feld **Standard Warenkorbnr.** und klicken Sie auf **Neu**. Dieser Warenkorb wird immer dann verwendet, wenn für einen Benutzer kein eigener Warenkorb erstellt wurde. Wir empfehlen, das Feld **Wiederkehrend** für diesen Warenkorb nicht zu aktivieren.  
1. Das Fenster **Auswählen – Warenkorb** wird angezeigt.  
   ![select-cart](../assets/select-cart.png)  
1. Vervollständigen Sie die Informationen für den Warenkorb und kehren Sie zur Seite **Beyond Carts Einrichtung** zurück.  
1. Wenn Sie mehrere Warenkörbe pro Benutzer zulassen möchten, aktivieren Sie den Schieberegler **Mehrere Warenkörbe pro User**.  
1. Wählen Sie im Dropdownmenü für das Feld **Standard Warenkorbverhalten** zwischen den Optionen **Direkt hinzufügen** oder **Benutzereingabe**. Bei der Option **Direkt hinzufügen** werden die Positionszeilen direkt aus dem Beleg mit der entsprechenden Menge in den Warenkorb hinzugefügt. Bei der Option **Benutzereingabe** werden Sie bei dem Übertrag der Positionszeilen in den Warenkorb dazu aufgefordert, die Artikelmenge anzugeben.    
1. Aktivieren Sie den Schieberegler **Warenkörbe nach Kreditornr. holen**, wenn Sie während dem Abrufen von Warenkorbzeilen zuerst nach dem Kreditor filtern möchten. Wenn Sie eine Bestellung erstellen und Warenkorbzeilen abrufen, werden Ihnen dann nincht alle Warenkorbzeilen des Systems angezeigt, sondern nur die Warenkorbzeilen, die für den ausgewählten Kreditor im System hinterlegt sind.  
1. Unter dem Bereich **Nummernserie** müssen Sie im Feld **Warenkorbnummern** eine neue Nummernserie für die Warenkörbe einrichten.  
1. Öffnen Sie das Dropdownmenü und wählen Sie aus dem Fenster die Option **Neu** aus.  
1. Erstellen Sie eine neue Nummernserie und weisen Sie diese über das Feld zu.  

Sie haben BEYOND Carts eingerichtet.  
Weitere Informationen dazu, wie Sie BEYOND Carts verwenden, erhalten Sie unter dem Kapitel [Warenkorb erstellen](../features/create-cart.md).  
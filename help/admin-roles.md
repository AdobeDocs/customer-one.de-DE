---
title: Administratorrollen
description: Mithilfe der Adobe Admin Console können Unternehmen eine flexible Verwaltungshierarchie definieren, die eine differenzierte Verwaltung des Produktzugriffs und der Verwendung von Adobe ermöglicht.
source-git-commit: c0035e17cc1ca97ac511aff3515b7a8f7866f32d
workflow-type: tm+mt
source-wordcount: '1639'
ht-degree: 0%

---


# Administratorrollen

Mithilfe der Adobe Admin Console können Unternehmen eine flexible Verwaltungshierarchie definieren, die eine differenzierte Verwaltung des Produktzugriffs und der Verwendung von Adobe ermöglicht. Ein oder mehrere Systemadministratoren, die während des Unternehmens-Onboarding-Prozesses bereitgestellt werden, befinden sich oben in der Hierarchie. Diese Systemadministratoren können Verantwortlichkeiten an andere Administratoren delegieren und gleichzeitig die Gesamtkontrolle beibehalten.

Verwaltungsrollen bieten den Unternehmen die folgenden Hauptvorteile:

* Kontrollierte Dezentralisierung der Verwaltungsaufgaben
* Schnellansicht der Produktzuweisungen - nach Benutzer und Produkt
* Funktion zum Zuweisen von Quoten zu Produktadministratoren

## Verwaltungshierarchie

Gilt für: Unternehmenskunden in der Adobe.

Die Verwaltungshierarchie kann für die individuellen Anforderungen Ihres Unternehmens verwendet werden. Ein Unternehmen kann beispielsweise verschiedene Administratoren für die Verwaltung von Berechtigungen für Adobe Creative Cloud- und Adobe Marketing Cloud-Angebote ernennen. Alternativ kann ein Unternehmen über verschiedene Administratoren verfügen, um Berechtigungen von Benutzern zu verwalten, die zu verschiedenen Geschäftsbereichen gehören.

>[!NOTE]
>
>Die Verwaltungshierarchie gilt nicht für Team-Kunden. Team-Kunden haben eine **Systemadministrator** Rolle. Der Vertragseigentümer (_zuvor als **Primärer Administrator**_) ist der Systemadministrator mit Zugriff auf die Vertragsdetails und den Abrechnungsverlauf. Wenn Sie der aktuelle Vertragseigentümer sind, können Sie einen bestehenden Systemadministrator (_ zuvor als **sekundärer Administrator**_) als Vertragseigentümer.

![Admin-Bild](assets/storage_admin.png)

_Hierarchie der Admin-Rollen_

| Rolle | Beschreibung |
|--- |--- |
| **Systemadministrator** | Superuser für die Organisation; erlaubt, alle Verwaltungsaufgaben in der Admin Console auszuführen.<br>Außerdem kann die folgende Verwaltungsfunktion anderen Benutzern zugewiesen werden: Produktadministrator, Produktprofiladministrator, Benutzergruppenadministrator, Bereitstellungsadministrator und Support-Administrator. |
| **Produkt-Admin** | Verwalten Sie die diesem Administrator zugewiesenen Produkte und alle damit verbundenen Verwaltungsfunktionen, darunter:<ul><li>Erstellen von Produktprofilen</li><li>Benutzer und Benutzergruppen zur Organisation hinzufügen, diese jedoch nicht entfernen</li><li>Hinzufügen oder Entfernen von Benutzern und Benutzergruppen aus Produktprofilen</li><li>Hinzufügen oder Entfernen von Produktprofiladministratoren aus Produktprofilen</li><li>Hinzufügen oder Entfernen anderer Produktadministratoren aus dem Produkt</li><li>Hinzufügen oder Entfernen von Gruppenadministratoren aus Gruppen</li></ul> |
| **Produktprofiladministrator** | Verwalten Sie die diesem Administrator zugewiesenen Produktprofilbeschreibungen sowie alle damit verbundenen Verwaltungsfunktionen, darunter:<ul><li>Benutzer und Benutzergruppen zur Organisation hinzufügen, diese jedoch nicht entfernen</li><li>Hinzufügen oder Entfernen von Benutzern und Benutzergruppen aus Produktprofilen</li><li>Produktberechtigungen Benutzern und Benutzergruppen aus Produktprofilen zuweisen oder widerrufen</li><li>Verwalten der Produktrollen von Benutzern und Benutzergruppen für Produktprofile |
| **Benutzergruppenadministrator** | Verwalten Sie die diesem Administrator zugewiesenen Benutzergruppenbeschreibungen und alle damit verbundenen Verwaltungsfunktionen, darunter:<ul><li>Hinzufügen oder Entfernen von Benutzern aus Gruppen</li><li>Hinzufügen oder Entfernen von Benutzergruppenadministratoren aus Gruppen |
| **Bereitstellungsadministrator** | Erstellt, verwaltet und stellt Softwarepakete und Updates für Endbenutzer bereit. |
| **Support-Admin** | Nicht administrative Rolle, die Zugriff auf unterstützungsbezogene Informationen hat, z. B. von Kunden gemeldete Problemberichte. |
| **Speicheradministrator** | Verwaltet die Speicherverwaltung des Unternehmens. Der Administrator kann den Speicherverbrauch sowohl aktiver als auch inaktiver Benutzer anzeigen und Inhalte an andere Empfänger übertragen. |

Eine detaillierte Liste der Berechtigungen und Berechtigungen für jede Administratorrolle finden Sie unter [Berechtigungen](#enterprise-admins-permissions-matrix).

## Unternehmensadministrator hinzufügen

Gilt für: Unternehmenskunden in der Adobe.

Als Administrator können Sie anderen Benutzern eine Administratorrolle zuweisen und ihnen die gleichen Berechtigungen wie Ihnen gewähren oder Berechtigungen für eine Rolle in Ihrer Administratorrolle in der Hierarchie gewähren, wie beschrieben [above](#administrative-hierarchy). Als Produktadministrator können Sie beispielsweise einem Benutzer Produktadministratorberechtigungen oder Produktprofil-Administratorberechtigungen erteilen, jedoch nicht Administratorberechtigungen für die Bereitstellung. Informationen zu den Berechtigungen für die Admin Console finden Sie unter [Berechtigungsmatrix](#enterprise-admins-permissions-matrix).

So fügen Sie einen Administrator hinzu oder laden ihn ein:

1. Im [Admin Console](https://adminconsole.adobe.com/)auswählen **Benutzer** > **Administratoren**.

   Alternativ können Sie zum entsprechenden Produkt, Produktprofil oder Benutzergruppe navigieren und zur **Administratoren** Registerkarte.

1. Klicken **Admin hinzufügen**.
1. Geben Sie einen Namen oder eine E-Mail-Adresse ein. Sie können nach vorhandenen Benutzern suchen oder einen neuen Benutzer hinzufügen, indem Sie eine gültige E-Mail-Adresse angeben und die Informationen auf dem Bildschirm ausfüllen.
1. Klicken **Nächste**. Eine Liste der Admin-Rollen wird angezeigt.

>[!NOTE]
>
>* Die Optionen auf diesem Bildschirm hängen von Ihrem Konto und Ihrer Administratorrolle ab. Sie können entweder dieselben Berechtigungen wie Sie haben, oder Berechtigungen für eine Rolle unter Ihrer in der Hierarchie gewähren.
>* Als Systemadministrator eines Teams können Sie nur eine Administratorrolle zuweisen: Systemadministrator.


1. Wählen Sie eine oder mehrere Admin-Rollen aus.
1. Wählen Sie für Admin-Typen wie Produktadministrator, Produktprofiladministrator und Benutzergruppenadministrator die spezifischen Produkte, Profile und Gruppen aus.

>[!NOTE]
>
>Für einen Produktprofiladministrator können Sie Profile für mehr als ein Produkt einbeziehen.

![Admin hinzufügen](assets/add-admin.png)

1. Überprüfen Sie die Administratorrollen, die dem Benutzer zugewiesen sind, und klicken Sie auf **Speichern**.

Der Benutzer erhält eine E-Mail-Einladung zu den neuen Administratorrechten von `message@adobe.com`.

Benutzer müssen auf **Erste Schritte** in der E-Mail, um Mitglied der Organisation zu werden. Wenn neue Administratoren die **Erste Schritte** in der E-Mail-Einladung enthalten, können sie sich nicht bei der Admin Console anmelden.

Im Rahmen des Anmeldeprozesses können Benutzer aufgefordert werden, ein Benutzerprofil einzurichten, wenn sie noch kein Adobe haben. Wenn mehrere Profile mit ihrer E-Mail-Adresse verknüpft sind, müssen Benutzer &quot;Team beitreten&quot;wählen (wenn Sie dazu aufgefordert werden) und dann das mit der neuen Organisation verknüpfte Profil auswählen.

![Bild mit Administratorrechten](assets/admin-get-started-email.png)

## Team-Administrator hinzufügen {#add-admin-teams}

Gilt für: Adobe stellt Kunden bereit.

Als Administrator können Sie anderen Benutzern die Systemadministratorrolle zuweisen und ihnen die gleichen Berechtigungen wie Ihnen gewähren.

So fügen Sie einen Systemadministrator hinzu oder laden einen Systemadministrator ein:

1. Wählen Sie in der Admin Console **Benutzer** > **Administratoren**.

   Eine Liste der vorhandenen Administratoren wird angezeigt.

1. Klicken **Admin hinzufügen**.

   Die **Hinzufügen eines Administrators** angezeigt.

1. Geben Sie einen Namen oder eine E-Mail-Adresse ein. Sie können nach vorhandenen Benutzern suchen oder einen neuen Benutzer hinzufügen, indem Sie eine gültige E-Mail-Adresse angeben und die Informationen auf dem Bildschirm ausfüllen.

   Standardmäßig ist &quot;Systemadministrator&quot;ausgewählt.

1. Klicken **Speichern**.

![Team-Admin-Bild](assets/teams-admin.png)

Da alle Benutzer in einer Team-Organisation Business-ID-Benutzer sind, erhalten sie eine E-Mail-Einladung zu den neuen Administratorrechten von `message@adobe.com`.
Benutzer müssen in der E-Mail auf Erste Schritte klicken, um der Organisation beizutreten.

Im Rahmen des Anmeldeprozesses können Benutzer aufgefordert werden, ein Benutzerprofil einzurichten, wenn sie noch kein Adobe haben. Wenn mehrere Profile mit ihrer E-Mail-Adresse verknüpft sind, müssen Benutzer &quot;Team beitreten&quot;wählen (wenn Sie dazu aufgefordert werden) und dann das mit der neuen Organisation verknüpfte Profil auswählen.

![Bild mit Administratorrechten](assets/admin-get-started-email.png)

## Administratorrolle &quot;Unternehmen bearbeiten&quot;

Gilt für: Unternehmenskunden in der Adobe.

Als Administrator können Sie die Administratorrolle für andere Administratoren bearbeiten, die sich in der Verwaltungshierarchie unter Ihnen befinden. Sie können beispielsweise Admin-Berechtigungen anderer Administratoren entfernen.

So bearbeiten Sie Admin-Rollen:

1. Wählen Sie in der Admin Console **Benutzer** > **Administratoren**. Die Liste der vorhandenen Administratoren wird angezeigt.

   Alternativ können Sie zum entsprechenden Produkt, Produktprofil oder Benutzergruppe navigieren und zur **Administratoren** Registerkarte.

1. Klicken Sie auf den Namen des zu bearbeitenden Administrators.
1. Im **Benutzerdetails** klicken ![icon](assets/one-console-ellipses.png) für **Administratorrechte** und wählen Sie **Administratorrechte bearbeiten**.

   ![Administratorrechte bearbeiten](assets/admin-rights-section.png)

1. Bearbeiten Sie die Administratorrechte und speichern Sie Ihre Änderungen.

## Administratorrolle für Teams bearbeiten

Gilt für: Adobe stellt Kunden bereit.

Als Systemadministrator der Teams können Sie die Systemadministratorberechtigungen anderer Administratoren entfernen.

Sperren der Systemadministratorberechtigungen:

1. Wählen Sie in der Admin Console **Benutzer** > **Administratoren**.

   Die Liste der vorhandenen Administratoren wird angezeigt.

1. Klicken Sie in den Benutzerdetails auf ![icon](assets/one-console-ellipses.png) rechts von der **Administratorrechte** und wählen Sie **Administratorrechte bearbeiten**.

   ![Administratorrechte bearbeiten](assets/admin-rights-section.png)

1. Bearbeiten Sie die Administratorrechte und speichern Sie Ihre Änderungen.

## Entfernen eines Administrators

Gilt für: Adobe stellt Unternehmenskunden bereit.

1. Um Administratorberechtigungen zu widerrufen, wählen Sie einen Benutzer aus und klicken Sie auf **Administrator entfernen**.

![Admin-Bild entfernen](assets/remove-admin.png)

>[!NOTE]
>
>Wenn Sie einen Administrator entfernen, wird der Benutzer nicht aus der Admin Console gelöscht, sondern nur die mit der Administratorrolle verknüpften Berechtigungen.

## Matrix der Berechtigungen von Unternehmensadministratoren

Gilt für: Unternehmenskunden in der Adobe.

In der folgenden Tabelle sind alle Berechtigungen für die verschiedenen Administratortypen aufgeführt, die nach den folgenden Funktionsbereichen kategorisiert sind:

### Identitätsverwaltung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Domäne hinzufügen (Domäne anfordern/anfordern) | ms |  |
| Anzeigen der Domänen- und Domänenliste | ms |  |
| Verwalten von Domain-Verschlüsselungsschlüsseln | ms |  |
| Standardrichtlinien für das Organisationskennwort verwalten | ms |  |
| Standardmäßige Richtlinien für das Organisationskennwort anzeigen | ms |  |

### Benutzerverwaltung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Benutzer zur Organisation hinzufügen | ms |  |
| Benutzer aus Organisation entfernen | ms |  |
| Anzeigen von Benutzerdetails und Auflistung | ms |  |
| Benutzerprofil bearbeiten | ms |  |
| Produktprofil zu Benutzer oder Gruppe hinzufügen | ms |  |
| Produktprofil für Benutzer oder Gruppe entfernen | ms |  |
| Hinzufügen von Produktprofilen zu mehreren Benutzern | ms |  |
| Anzeigen von Produktprofilen für einen Benutzer | ms |  |
| Produktbenutzerliste anzeigen | ms |  |
| Massenfügen Sie Benutzer zur Organisation hinzu | ms |  |

### Administratorverwaltung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Einen Org-Admin einem Benutzer gewähren | ms |  |
| Org-Admin von einem Benutzer abrufen | ms |  |
| Produkt-Lizenzadministrator für einen Benutzer gewähren | ms |  |
| Produktlizenzadministrator von einem Benutzer abrufen | ms |  |
| Bereitstellung eines Admins für einen Benutzer gewähren | ms |  |
| Deployment Admin von einem Benutzer abrufen | ms |  |
| Gewähren eines Benutzergruppenadministrators für einen Benutzer | ms |  |
| Benutzergruppenadministrator von einem Benutzer abrufen | ms |  |
| Gewähren der Produkteigentümeradministration für einen Benutzer | ms |  |
| Den Produkteigentümer-Administrator von einem Benutzer abrufen | ms |  |

### Konfiguration der Produktlizenzen

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Produktberechtigungen für Organisation gewähren |  |  |
| Produktberechtigungen aus der Organisation entfernen |  |  |
| Gesamtanzahl der Lizenzen anzeigen, die der Organisation gehören | ms |  |
| Verfügbare Produkte und Produktfamilien anzeigen | ms |  |
| Produktlizenzbeschreibungen/Daten bearbeiten | ms |  |
| Bereitstellen einer Produktlizenz für einen Benutzer | ms |  |
| Deaktivieren der Produktlizenz von einem Benutzer | ms |  |
| Neue Produktlizenzkonfiguration hinzufügen | ms |  |
| Konfiguration des Produktlizenzdienstes bearbeiten | ms |  |
| Konfiguration des Produktlizenzdienstes löschen | ms |  |
| Entfernen des Produktzugriffs von einem Benutzer (Entfernen aus allen Konfigurationen) | ms |  |

### Speicherverwaltung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Anzeigen aktiver und inaktiver Benutzerordner | ms |  |
| Löschen von Ordnern inaktiver Benutzer und Übertragen von Inhalten | ms |  |

### Implementierung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Registerkarte &quot;Pakete anzeigen/verwenden&quot; | ms |  |

### Support

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Registerkarte &quot;Support&quot; | ms |  |
| Support-Fälle verwalten | ms | ms |

### Benutzergruppenverwaltung

| Berechtigung | Systemadministrator | Support-Administrator |
|--- |--- |--- |
| Benutzergruppe erstellen | ms |  |
| Benutzergruppe löschen | ms |  |
| Benutzer zur Benutzergruppe hinzufügen | ms |  |
| Benutzer aus Benutzergruppe entfernen | ms |  |
| Zuweisen einer Benutzergruppe zur Produktlizenz | ms |  |
| Benutzergruppe aus Produktlizenz entfernen | ms |  |
| Mitglied der Benutzergruppe anzeigen | ms | ms |
| Liste der Benutzergruppen anzeigen | ms | ms |

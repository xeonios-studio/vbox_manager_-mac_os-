# VirtualBox VM Setup Tool For Windows

Dieses Projekt bietet ein Tool zum Erstellen und Konfigurieren von macOS-VMs auf Oracle VirtualBox unter Windows. Mit dieser Anwendung kannst du eine virtuelle Maschine (VM) für macOS erstellen, die nötigen Einstellungen vornehmen (z. B. CPU, RAM, Grafikspeicher) und eine ISO für die Installation auswählen.

## Funktionen

- Erstellung von macOS-VMs mit unterschiedlichen macOS-Versionen (Monterey, Big Sur, Ventura, Catalina).
- Unterstützung von EFI-Boot und 3D-Grafikbeschleunigung.
- Automatisierte CPU-ID-Konfiguration für macOS.
- Einfache Integration von benutzerdefinierten ISO-Dateien über einen Datei-Dialog.
- Automatische Auswahl der Festplatte und Netzwerkeinstellungen für die VM.
- Möglichkeit, Secure Boot und weitere macOS-spezifische Einstellungen zu aktivieren.

## OS-Support

- Monterey.
- Big Sur.
- Ventura.
- Catalina.

## Voraussetzungen

- **Oracle VirtualBox**: Stelle sicher, dass Oracle VirtualBox installiert ist. Die `VBoxManage.exe` muss im angegebenen Verzeichnis vorhanden sein.
- **.NET Framework 4.8.1** oder höher: Das Tool wurde mit Visual Basic .NET entwickelt und benötigt das .NET Framework zur Ausführung.
- **macOS ISO-Datei**: Eine macOS-Installations-ISO-Datei wird benötigt, um macOS auf der VM zu installieren.

## Installation

1. **Oracle VirtualBox installieren**:
   Lade und installiere Oracle VirtualBox von der offiziellen Website: https://www.virtualbox.org/

2. **Visual Basic .NET Projekt**:
   - Lade das Repository herunter oder klone es mit Git:
     ```bash
     git clone https://github.com/xeonios-studio/VirtualBox-VM-Setup.git
     ```
   - Öffne das Projekt in Visual Studio.
   - Stelle sicher, dass alle erforderlichen .NET-Abhängigkeiten vorhanden sind.

3. **Programm starten**:
   - Baue und starte das Projekt in Visual Studio.
   - Klicke auf den "Erstellen"-Button, um eine neue macOS-VM zu erstellen.
   - Wähle die macOS-Version und die ISO-Datei aus, die du für die Installation verwenden möchtest.

## Nutzung

1. **VM erstellen**:
   - Wähle eine macOS-Version aus der Dropdown-Liste.
   - Klicke auf "Erstellen", um eine neue VM zu erstellen.
   - Die VM wird automatisch mit den empfohlenen Einstellungen (RAM, CPU, Festplatte) und EFI-Firmware konfiguriert.

2. **Benutzerdefinierte ISO auswählen**:
   - Nach dem Klick auf "Erstellen" öffnet sich ein Dialogfenster, in dem du die macOS-ISO-Datei auswählen kannst.
   - Stelle sicher, dass die ISO-Datei korrekt und für die Installation von macOS geeignet ist.

3. **Einstellungen**:
   - Das Tool wird auch Optionen wie 3D-Grafikbeschleunigung, Secure Boot und andere macOS-spezifische Einstellungen automatisch vornehmen.

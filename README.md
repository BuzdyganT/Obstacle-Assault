# Obstacle Assault - Unreal Engine 5.7.4 C++

Projekt zrealizowany w ramach kursu **"Unreal Engine 5 C++ Game Development"**. Głównym celem projektu jest nauka fundamentów silnika Unreal Engine, programowania logiki w C++ oraz integracji kodu z systemem Blueprints.

## 🛠 Technologie i Narzędzia
* **Silnik:** Unreal Engine 5.7.4
* **Język:** C++
* **IDE:** JetBrains Rider
* **System kontroli wersji:** Git

## 📦 Wymagane zasoby (Dependencies)

Ze względu na ograniczenia rozmiaru repozytorium GitHub (limit 100MB na plik), ciężkie modele 3D oraz tekstury 4K **nie zostały dołączone do kodu źródłowego**.

Aby projekt wyświetlał się poprawnie, należy pobrać poniższe darmowe paczki z platformy **Fab** i umieścić je w odpowiednich folderach w głównym katalogu `Content/`:

| Paczka z Fab | Docelowy folder w `/Content/` |
| :--- | :--- |
| [Stylized Eastern Village](https://www.fab.com/listings/9841fee2-683f-4e68-adb8-bafec270a251) | `Asian_Village` |
| [Construction Site VOL.1](https://www.fab.com/listings/ba44a508-bfa5-444c-bbf4-69e8b5dee530) | `Construction_VOL1` |
| [Survival Character FREE](https://www.fab.com/listings/11d20d01-b764-4936-8163-cb20d05c369e) | `Survival_Character` |

## 🚀 Jak uruchomić projekt
1. Sklonuj repozytorium na swój dysk.
2. Pobierz powyższe assety i umieść je wewnątrz folderu `Content`.
3. Otwórz plik `.uproject` bezpośrednio w JetBrains Rider **LUB** kliknij na niego prawym przyciskiem myszy i wybierz opcję **"Generate Visual Studio project files"**.
4. Otwórz projekt w swoim IDE i skompiluj kod (skrót `Ctrl + Alt + F11` dla Live Coding w działającym silniku).
5. Uruchom silnik Unreal Engine.
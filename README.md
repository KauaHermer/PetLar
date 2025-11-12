# 🐾 PetLar

O **PetLar** é um aplicativo desenvolvido em **Flutter** com backend em **PHP**, destinado a conectar pessoas, ONGs e voluntários para adoção e cuidado de animais.

---

## 📁 Estrutura do Projeto

PetLar/
│
├── PetLar/ # Aplicativo Flutter
│
└── htdocs/
└── petlar_api/ # Backend PHP

## ⚙️ Configuração do Backend (PHP)

1. Instale o **XAMPP**.
2. Copie a pasta `petlar_api` para dentro de:
C:\xampp\htdocs\

3. O backend ficará acessível em:
http://localhost/petlar_api/

---

## 🧩 Configuração do `php.ini`

Abra o arquivo:
C:\xampp\php\php.ini

Cole ou habilite as seguintes linhas, removendo o ponto e vírgula `;` caso exista:

extension=pdo_pgsql
extension=pgsql
extension=fileinfo
Salve o arquivo e reinicie o Apache no painel do XAMPP.

📲 Configuração do Flutter
Abra a pasta PetLar no terminal.

Rode o comando:
flutter pub get

Execute o aplicativo:
flutter run
Para executar no navegador:
flutter run -d chrome
yaml
Copiar código

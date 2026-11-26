# Wytyczne dla Asystentów AI (GitHub Copilot, Cursor, Claude)

Pracując w tym repozytorium, bezwzględnie przestrzegaj poniższych zasad:

1. **Język komunikacji:** Wszystkie odpowiedzi, dokumentacja oraz komentarze w kodzie tworzone są w języku polskim (lub angielskim tam, gdzie wymaga tego standard biblioteki).
2. **Conventional Commits:** Wszystkie commity muszą mieć format: `feat:`, `fix:`, `refactor:`, `test:`, `docs:`, `chore:`.
3. **Integralność testów:** NIGDY nie usuwaj ani nie wyciszaj istniejących testów bez wyraźnego polecenia. Dodając nowy kod, zawsze dopisz testy jednostkowe lub integracyjne.
4. **Bezpieczeństwo sekretów:** ZAKAZ wprowadzania zaszyfrowanych lub jawnych kluczy API, tokenów, haseł i plików `.env` do repozytorium. Używaj zmiennych środowiskowych zdefiniowanych w `.env.example`.
5. **Jakość kodu i typowanie:** Przestrzegaj reguł lintera (Ruff / ESLint) i formowania. Używaj ścisłego typowania (type hints w Pythonie / TypeScript).
6. **Self-Hosted Runner i serwer:** Wszelkie operacje budowania, testów i migracji powinny być przystosowane do uruchamiania na lokalnym serwerze (Docker / self-hosted runner).

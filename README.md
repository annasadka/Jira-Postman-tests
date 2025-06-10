# Jira-Postman-Issues-CRUD

## Opis
Projekt prezentuje testowanie operacji CRUD na zgłoszeniach w Jira Cloud przez API, z użyciem Postmana i automatycznych testów.

## Scenariusze testowe

1. **Utworzenie zgłoszenia**
   - POST /rest/api/3/issue
   - Sprawdzenie statusu 201 i obecności klucza zgłoszenia

2. **Pobranie zgłoszenia**
   - GET /rest/api/3/issue/{issueKey}
   - Sprawdzenie statusu 200 i obecności tytułu

3. **Aktualizacja zgłoszenia**
   - PUT /rest/api/3/issue/{issueKey}
   - Sprawdzenie statusu 204

4. **Utworzenie zgłoszenia z opisem**
   - POST /rest/api/3/issue
   - Sprawdzenie statusu 201

5. **Usunięcie zgłoszenia**
   - DELETE /rest/api/3/issue/{issueKey}
   - Sprawdzenie statusu 204

6. **Test negatywny**
   - GET nieistniejącego zgłoszenia
   - Sprawdzenie statusu 404



# Marco Zero — Odômetro de Obras

by DVAbrão Serviços · app irmão do SLIR (mesmo motor de GPS e mesmo visual).

- `web/` — o app (HTML único). Abre direto no navegador para testar.
- `android/` — casca nativa (WebView + GPS em foreground service), package `com.dvabrao.marcozero`.
- `.github/workflows/gerar-apk.yml` — a cada push na `main` o GitHub compila e publica o APK em **Releases**.

Estaca padrão: 20 m (Est 6 + 15,00 = 135 m), configurável.
Formato do ponto: `P001 - km 0,135 - Est 6 + 15,00 - -21.154157, -47.697923`

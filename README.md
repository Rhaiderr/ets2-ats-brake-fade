# Brake Fade for ETS2 & ATS

[English](#english) · [Português (Brasil)](#português-brasil)

**[⬇ Download Brake Fade 0.4.0-rc6 (ZIP)](https://github.com/Rhaiderr/ets2-ats-brake-fade/releases/download/v0.4.0-rc6/ets2-ats-brake-fade.zip)** · [Release notes](https://github.com/Rhaiderr/ets2-ats-brake-fade/releases/tag/v0.4.0-rc6) · [ModHub](https://rhaiderr.github.io/mod-hub/)

![Brake Fade promotional artwork showing a truck with hot brakes on a Brazilian mountain road](https://rhaiderr.github.io/mod-hub/assets/brake-fade.jpg)

## English

On long descents, repeated service braking heats the brakes. Brake Fade simulates the resulting loss of braking power and recovery as the brakes cool. The truck and attached trailers have separate temperatures and smoke effects. The HUD shows temperatures and remaining braking efficiency.

### Compatibility

- **Euro Truck Simulator 2 1.62.3.3 x64** — Windows, DirectX 11, single player. Native service-brake fade and trailer smoke were confirmed in-game on the RC6.
- **American Truck Simulator 1.62.2.2 x64** — experimental profile. In-game validation is pending, and the RC6 native service-brake hook is currently mapped for ETS2. Full braking behavior on ATS is pending.
- The installer checks the exact game executable. Other builds may require an update to the plugin.

### Installation and controls

1. Close the game and extract the complete ZIP.
2. Run `install.bat` for ETS2. For the experimental ATS profile, run `install.bat -Game ATS`. For a custom Steam library, add `-GamePlugins "…\bin\win_x64\plugins"`.
3. Confirm the displayed destination. The installer backs up an existing Brake Fade DLL and INI and preserves your active settings. Disable any other brake plugin before installing.
4. Start the game. Press **Shift+F12** to open settings and **Shift+F6** to toggle the fixed HUD. Keep your usual keyboard or pedal bindings in ETS2.

Use the settings panel to adjust heating, cooling, the fade curve, smoke, alerts and HUD size and position. The default preset starts fade at 300 °C and reaches 25% remaining efficiency at 600 °C. Optional sound requires local PCM16 WAV files at `sounds/BrakeFadeBR/brake_low.wav` and `sounds/BrakeFadeBR/brake_high.wav` beside the DLL.

To uninstall, close the game and remove `brake_fade_br.dll` from `bin/win_x64/plugins`. To roll back, restore the previous files from `plugins/backups/BrakeFadeBR/`.

## Português (Brasil)

Em descidas longas, o uso repetido do freio de serviço aquece os freios. O Brake Fade simula a perda de força de frenagem e a recuperação durante o resfriamento. Caminhão e carretas engatadas têm temperaturas e efeitos de fumaça separados. O HUD exibe a temperatura e a eficiência restante.

### Compatibilidade

- **Euro Truck Simulator 2 1.62.3.3 x64** — Windows, DirectX 11, modo individual. A perda de eficiência no freio de serviço e a fumaça da carreta foram confirmadas no jogo na RC6.
- **American Truck Simulator 1.62.2.2 x64** — perfil experimental. A validação em jogo está pendente, e a integração nativa do freio de serviço da RC6 está mapeada para ETS2. O funcionamento completo da frenagem no ATS segue pendente.
- O instalador confere o executável exato. Outras versões podem precisar de uma atualização do plugin.

### Instalação e atalhos

1. Feche o jogo e extraia o ZIP completo.
2. Execute `install.bat` para ETS2. Para o perfil experimental do ATS, execute `install.bat -Game ATS`. Se a biblioteca da Steam estiver em outra pasta, acrescente `-GamePlugins "…\bin\win_x64\plugins"`.
3. Confira o destino mostrado. O instalador faz backup da DLL e do INI anteriores e preserva suas configurações. Desative outros plugins de freio antes de instalar.
4. Abra o jogo. Use **Shift+F12** para abrir as configurações e **Shift+F6** para mostrar ou ocultar o HUD fixo. Mantenha os controles de teclado ou pedal que você já usa no ETS2.

No menu, ajuste aquecimento, resfriamento, curva de perda de eficiência, fumaça, avisos, tamanho e posição do HUD. O preset padrão começa a reduzir a eficiência a 300 °C e chega a 25% de eficiência restante a 600 °C. O áudio opcional precisa dos WAVs PCM16 locais `sounds/BrakeFadeBR/brake_low.wav` e `sounds/BrakeFadeBR/brake_high.wav` ao lado da DLL.

Para desinstalar, feche o jogo e remova `brake_fade_br.dll` de `bin/win_x64/plugins`. Para voltar à versão anterior, restaure os arquivos de `plugins/backups/BrakeFadeBR/`.

<!-- Adicionar prints do jogo quando estiverem disponíveis. -->

# Задание 6 — Unity WebXR

**Запуск:** https://mariikkkk.github.io/webar-pr6/

Открыть в Chrome на Android, дождаться загрузки и нажать AR. Разрешить доступ к камере. На компьютере доступен 3D-предпросмотр. Проверено на OnePlus 15, Android 17, Chrome 156.0.8078.47.

Куб находится в viewer-space: его положение и ориентация обновляются относительно камеры каждый кадр. При движении телефона куб остаётся в центре экрана. Закрепление на реальной поверхности не является частью этого сценария.

## Сборка

- Unity 6000.6.2f1; De-Panther WebXR Exporter и Interactions 0.25.0.
- Built-in Render Pipeline; WebXRCamera, два WebXRController, WebXRLoader.
- AR reference space: viewer.
- WebGL, WebXRFullView2020.
- Compression Format Disabled, Decompression Fallback false, Threads Support false.
- Размер каталога исходной WebGL-сборки: 29 086 069 байт.

В репозитории находится готовая браузерная сборка, а не полный проект редактора Unity. Редактор для просмотра не нужен.

WebXR Exporter распространяется по Apache-2.0; лицензия и сторонние уведомления находятся в `licenses/`. К компонентам движка применяются условия Unity.

Задание 5: [Three.js WebAR](https://mariikkkk.github.io/webar-pr5/) · [репозиторий](https://github.com/mariikkkk/webar-pr5).

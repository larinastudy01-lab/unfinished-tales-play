# 遊戲素材

三樓圖片已從 `src/assest/third-ready/` 由 Vite 匯入，對照表在 `src/candy/third-assets.ts`。其他本地圖片也可以放在這裡，再於 `src/candy/art.ts` 的 `IMAGE_ASSETS` 填入 visualKey、路徑與顯示尺寸；請保留既有 `...THIRD_FLOOR_ASSETS`。完整範例請看根目錄 `README.md`。物理碰撞尺寸由 `config.ts` 與 `levels.ts` 管理，不由圖片尺寸決定。

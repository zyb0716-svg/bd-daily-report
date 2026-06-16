# BD GitHub Pages 本地发布包

生成时间：2026-06-16 13:50:17

本目录只包含可以发布到 GitHub Pages 的静态文件：

- `index.html`：正式报告入口页
- `bd_m1_m3_monthly_forecast_chart.png`：报告图表
- `short_term_final_forecast_summary.csv`：预测摘要
- `final_forecast_lock.csv`：锁定预测与口径信息
- `short_term_final_backtest_summary.csv`：正式回测摘要
- `publish_metadata.json`：本次打包元数据

手动发布到 GitHub Pages 的推荐命令：

```powershell
cd /d "D:\BD问题研究\github_pages_publish\bd-daily-report"
Copy-Item -Force "D:\BD问题研究\github_pages_publish\site_package\*" "D:\BD问题研究\github_pages_publish\bd-daily-report\"
git add .
git commit -m "Update BD report"
git push origin main
```

GitHub Pages 地址：

https://zyb0716-svg.github.io/bd-daily-report/

注意：自动模型任务只生成本地包，不执行 `git push`。

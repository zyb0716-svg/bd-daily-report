# BD GitHub Pages publish package
Generated at: 2026-07-05 21:23:24

Files:
- index.html: formal report entry
- bd_m1_m3_monthly_forecast_chart.png: report chart
- short_term_final_forecast_summary.csv: forecast summary
- final_forecast_lock.csv: locked forecast and metrics
- short_term_final_backtest_summary.csv: backtest summary
- publish_metadata.json: package metadata

Manual publish:
```powershell
Set-Location -LiteralPath "D:\BD问题研究\github_pages_publish\bd-daily-report"
Copy-Item -Path "D:\BD问题研究\github_pages_publish\site_package\*" -Destination "D:\BD问题研究\github_pages_publish\bd-daily-report" -Force
git add .
git commit -m "Update BD report"
git push origin main
```

GitHub Pages URL:
https://zyb0716-svg.github.io/bd-daily-report/

Google Analytics measurement ID:
G-11B1CLMF7R

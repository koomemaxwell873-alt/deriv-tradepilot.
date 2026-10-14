# Deriv TradePilot

Static web prototype for viewing simple market signals and testing demo-only Deriv contracts.

## Files
- `index.html`: dashboard
- `styles.css`: responsive layout
- `app.js`: WebSocket connection and prototype signal/contract logic
- `SAFETY.md`: setup and limitations

## Setup
1. Register your own application with Deriv and use its app ID.
2. Create a demo account API token with only required permissions.
3. Host these files over HTTPS (for example, GitHub Pages after committing them).
4. Connect using a demo token and confirm the account is identified as virtual/demo.
5. Keep automation disabled while inspecting signals.

## Important
This is an experimental prototype, not a verified profitable strategy. The signal is a simple recent-tick heuristic. Settlement and account-level profit/loss tracking are not implemented; the trade-count cap is not a complete risk-management system. Keep automation off until thoroughly tested. Never commit API tokens or use a real-money token.

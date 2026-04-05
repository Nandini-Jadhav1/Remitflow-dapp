# 🔒 RemitFlow Security Checklist

## ✅ Wallet Security
- [x] No private keys stored anywhere
- [x] All signing done locally in Freighter
- [x] Non-custodial — app never touches funds
- [x] Connection requires explicit user approval

## ✅ Transaction Security
- [x] Address validation (56 chars, starts with G)
- [x] Balance check before sending
- [x] 30 second transaction timeout
- [x] Fee Bump uses controlled fee multiplier

## ✅ Frontend Security
- [x] No sensitive data in localStorage
- [x] All API calls use HTTPS
- [x] No hardcoded secrets
- [x] XSS prevention via React

## ✅ Smart Contract Security
- [x] sender.require_auth() on all writes
- [x] Input validation on all functions
- [x] Events emitted for all changes

## ✅ Deployment Security
- [x] Deployed on Vercel with HTTPS
- [x] .gitignore configured
- [x] No secrets in GitHub repo
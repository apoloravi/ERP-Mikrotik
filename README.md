# ERP-Mikrotik
ERP MIkrotik com Sistemas de Faturas MercadoPago
# ERP para Provedores de Internet

Sistema completo de gestão para provedores com:
- Integração Mikrotik via API
- Emissão de faturas com PIX (Mercado Pago)
- Área do cliente
- Suspensão automática

## Requisitos
- PHP 7.4+
- MySQL 5.7+
- Mikrotik RouterOS 6.45+

## Instalação
```bash
git clone https://github.com/apoloravi/erp-provedor.git
cd erp-provedor
chmod +x scripts/erp-mikrotik.sh
./scripts/erp-mikrotik.sh

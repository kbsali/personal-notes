### 2025-06- Brief project
- OTA : Online Travel Agency
- DMC : Destination Management Company
- Bedbank : **[Bed banks](https://www.altexsoft.com/blog/bed-banks-hotelbeds-travco-bonotel-hotelspro/)** (also called **[wholesalers](https://www.altexsoft.com/glossary/wholesaler/)**) are B2B companies that purchase rooms from accommodation providers in bulk at a discounted, static price for specific dates and sell them to [OTAs](https://www.altexsoft.com/blog/online-travel-agency-business/), airlines, [destination management companies](https://www.altexsoft.com/blog/destination-management-companies/), or [tour operators](https://www.altexsoft.com/blog/tour-operator-software/).
### 2025-06- Brief CTO position
BRIEFING PARA EL FUTURO CTO

(Versión sincera‑pero‑seductora: sí, queremos tu cerebro y probablemente parte de tu alma)

⸻

1. Quiénes somos
• Founders: Ex‑travel‑tech nerds con un exit decente, agenda cargada de bedbanks, OTAs y DMCs, y una peligrosa mezcla de ambición + sentido del humor cuestionable.
• Visión: Que los pagos B2B en turismo dejen de parecer contrabando con mulas y se parezcan más a un checkout de Stripe (pero multimoneda, multirriesgo y con sabor a Dubái).
• Estado actual:
• Pain points validados con ±20 partners (OTAs, bedbanks y DMCs de alto riesgo).
• Wireframes en Figma, modelo financiero (sudores fríos incluidos) y conversaciones con dos EMIs para white‑label de licencia.
• Financiación semilla asegurada (cash propio) para 18 meses de runway real, no powerpoint‑runway.

⸻

2. Problema que vamos a destripar
3. Automatización post‑checkout entre OTAs→bedbanks→DMCs→hoteles.
4. FX & risk mitigation en divisas exóticas (peso ARS, baht, real, etc.).
5. Fiscalidad optimizada: split‑payment para capturar margen en jurisdicción low‑tax (Ej.: Dubái).
6. Onboarding casi sin fricción: datos básicos + verificación fiscal; compliance as‑a‑service vía proveedor.
7. Financiación de working‑capital (líneas de crédito sobre reservas futuras, versión 2.0).

⸻

3. Producto en versión TL;DR

Módulo Para qué existe Estado Demonios técnicos que te tocará domar
Core Ledger Registra, netea y liquida flujos multientidad PoC en Node + Postgres Consistencia ACID y latency < 1 s
FX Engine Conversión en ~40 divisas con forward cover Integración preliminar con proveedor Gestión de riesgo + fallback rates
Tax/Settlement Split Dispersa márgenes a cuentas “Dubái” / “Local” Diseño en Notion (sí, duele) Cálculo fiscal por jurisdicción, reglas BEPS
Fast Onboarding KYB light + score de riesgo Vendor shortlist hecho Workflow + match con compliance
Credit Scoring Anticipos contra reservas futuras Fase de research Modelo machine‑learning & data feeds

Stack preliminar sugerido (abierto a tu herejía si justificada):
• Backend: TypeScript + NestJS (event‑driven, CQRS).
• DB: Postgres + Timescale para eventos financieros.
• Infra: AWS EKS, Terraform, GitHub Actions.
• Data: Python + DuckDB / Kafka para pipes y scoring.
• Security/Compliance: Hashicorp Vault, OPA, Trino‑based audit lake.

⸻

4. Roadmap high‑level

Q Hito producto Hito negocio
Q3‑ 2025 MVP operacional con un bedbank (EU) y 3 DMCs (AR, TH, EG). Licencia EMI white‑label cerrada, contrato piloto firmado.
Q4‑ 2025 Módulo FX live, settlement D+3, dashboard clientes. 10 M USD TPV, seed‑extension si métricas pintan bien.
Q2‑ 2026 Línea de crédito piloto (factoring reservas). 50 M USD TPV, expansión a 2 nuevas licencias (UE, LATAM).


⸻

5. Qué esperamos de la criatura (aka tú)
• Visión técnica + gusto por la mugre regulatoria. Has visto pagos de cerca (PSP, EMI, banco digital o similar).
• Arquitecto pragmático: Event sourcing, idempotencia y reconciliación no son buzzwords, son desayuno.
• Builder‑in‑chief: Primer año escribirás código, montarás pipelines y te pelearás con auditores; luego ficharás y liderarás un equipo de 10‑15 ingenieros.
• DevSecOps mindset: Enjoy breaking things and showing the regulator the logs.
• Empatía con negocio: Entiendes que una feature sin licencias/compliance es un bonito post en Medium.
• Experiencia nice‑to‑have:
• Issuing / acquiring APIs (Nium, Stripe Treasury, Marqeta, WEX, etc.).
• FX or treasury systems.
• Data science aplicado a risk/credit.
• Haber sobrevivido a una auditoría PCI‑DSS sin perder el alma.

⸻

6. Qué ofrecemos (además de canas prematuras)
• Co‑founder title & equity competitivo (+ vesting 4y / 1y cliff).
• Salario inicial acorde a early‑stage (paga las facturas, no la Ferrari).
• Libertad tecnológica real: si puedes justificar, lo construimos.
• Remote‑first con HQ mediterráneo → reuniones presenciales trimestrales en sitio con playa decente.
• Budget de formación & conferencias (compliance no cuenta como diversión, sorry).
• Opcional: Relocation to Dubái o Mallorca si prefieres sol fiscal o sol literal.

⸻

7. Proceso de selección (rápido, prometido)
8. Call intro 30 ′ con founders → alineamos motivaciones.
9. Challenge técnico 48 h (arquitectura + caso de riesgo FX).
10. Deep dive product‑regulatorio con advisor legal y CFO.
11. Oferta (incluye cap‑table y proyecciones para que veas la película completa).

Si has leído hasta aquí sin bostezar, manda un mail a cto@[stealthname].io con:
• Enlace GitHub/LinkedIn.
• Tres líneas sobre la mayor pifia que has protagonizado en pagos y cómo no acabaste en la cárcel.
• Una idea para acortar el settlement LATAM↔UE a < 24 h sin hipotecar la empresa.

Nos vemos en la trinchera.

— Monday & Co.
### 2025-06- Pedro...
- Pedro Brucher
	- relacion con el sector turismo
	- y tecnica
		- ya monté 2 empresas de estas
		- mucho conocimiento en turismo, menos en pago
- Pedro Sosa - CEO/CPO
	- conocimiento de la industria de pagos
	- Local billing : negociaba cuentas
		- abria / cerraba las cuentas
		- relacion etre la empresa y las entidades bancaria
	- fundador "rock pay"
		- consultor de esto porque muchos contactos
- Samuel (Dubai) - CEO / Director Comercial (relacion con el sector turismo)
	- Logitravel -> Corte Ingles
	- Comercial de la ostia
- CFO (Dubai 20-30 anyos)
	- Hotelbeds CFO
	- E-bury
	- conocimiento financiero & turismo
	- Turismo
		- lo que existe hoy, manana no
		- producto con descuentos complejo
		- pago por adelanto
		- volumen enorme (~500 eur / ticket medio)
		- <50M eur = empresa pequena
		- problema : industria global
			- FX, como se paga, pagos, confianza...
- CTO
	- Pedro B : no tiene tiempo y no se ve tan bueno
	- Gestion del proyecto tecnico
- ---
- Proveedor - empresa con licencia banco
	- guardar pasta de los demas
	- Piggy Bucking
	- White label
- mientras sacamos nuesetra licensia
	- Canada : licensia mas facil
	- Dubai : money license
- Funding y reparticion
	- hablado nada
- Sacar MVP y 2/3 clientes pilotos durante 6 meses
	- ir a pedir pasta y escalar el proyecto
	- Buscar a WebBeds (giant) de manera muy generosa
	- nos utiliza como forma de pago obligatoria
		- abre las puertas a mas clientes
- Diferencia de travelgate
	- no es muy intensivo en servidores
	- muchas transacciones de dinero
		- ~40.000 peticiones / dia
- proyecto
	- pagos entre distribuidor <-> distribuidor
	- agencia online (eg. Logitravel) <-> DMC en tailandia (<-> hotel)
		- DMC = deposito de 1Meur a cambio de 100 plazas / dia durante 100 dias
		- TAM = pequeno
		- estrategia : enfocar al principio
	- soluciones existantes
		- hay cada vez mas, pero nadie lo ha clavado
			- Travel Ledger
	- cuenta nuestra
		- sub-accounts = wallet para
			- pagar y recibir (con un IBAN-virtual)
			- transferencia bancaria
			- transferencias internas (gratis)
		- FX = tema clave (cobrando algo mas te quedas el cambio)
		- Crear empresa en Dubai
			- tax-free...
		- Creditos a futuro
			- "3.5M eur por cobrar hasta agosto"
				- puede cobrar ahora mismo pero con 
	- en cuanto haya volumen -> se puede hacer pasta de varias formas
	- Settlement / reconciliacion de forma automatica
- Pasta
	- MVP auto-financiado
	- Pasta y/ o trabajo
- Calendario
	- cuanto antes mejor
	- ahora : estimar cuanto dinero / proveedores
	- 
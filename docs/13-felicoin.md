# 13 · FELICOIN, el medio de pago de Abitare

![FELICOIN](../assets/FELICOIN.3mf)

## 1. Qué es

La FELICOIN es el medio de pago interno de Abitare. Funciona como un saldo prepagado: el cliente consigna pesos, recibe FELICOIN en su billetera y con ellas paga el apartado, el arriendo o los servicios de la inmobiliaria. Además, cada pago le suma puntos de fidelidad.

| Característica | Definición |
|---|---|
| Nombre | FELICOIN |
| Símbolo | F con doble trazo (₣) · abreviatura FLC |
| Valor | 1 FLC = $1.000 COP, fijo (no sube ni baja) |
| Dónde se usa | Dentro de Abitare: apartados, arriendos y servicios. A futuro, en comercios aliados. |
| Cómo se consigue | 1. Cargando saldo (pesos → FLC). 2. Como premio del programa de fidelidad. |
| Dónde queda registrada | Contrato inteligente en red de prueba (Ethereum Sepolia), igual que el prototipo actual. |

## 2. Por qué 1 FLC = $1.000

La FELICOIN se ubica en el rango de una moneda media: más que una moneda nueva de pocos centavos de dólar y menos que las grandes. La diferencia es que su valor es fijo, porque está respaldada por los pesos que el cliente consigna en Abitare.

| Moneda | Tipo | Precio aprox. (US$) | Precio aprox. (COP) |
|---|---|---|---|
| Bitcoin (BTC) | La más popular | 77.000 | 249 millones |
| Ethereum (ETH) | Segunda más popular | 2.250 | 7,3 millones |
| Sui (SUI) | Red reciente (2023) | 0,87 | 2.800 |
| **FELICOIN (FLC)** | **Medio de pago de Abitare** | **0,31** | **1.000 (fijo)** |
| Cardano (ADA) | Moneda media | 0,20 | 630 |
| Pi Network (PI) | Red reciente (2025) | 0,08 | 250 |

Precios de referencia de la primera semana de noviembre de 2026, con un dólar a $3.235. Las demás monedas cambian de precio todos los días; la FELICOIN no.

Ejemplo: un apartado de $2.000.000 equivale a 2.000 FLC.

## 3. Cómo circula

| Paso | Quién | Qué pasa |
|---|---|---|
| 1 | Cliente | Consigna pesos en la cuenta de Abitare. |
| 2 | Asesor | Carga el saldo equivalente en FLC a la billetera del cliente. |
| 3 | Cliente | Paga el apartado o el arriendo con FLC desde la página. |
| 4 | Contrato inteligente | Confirma el pago, bloquea el inmueble y suma los puntos. |
| 5 | Asesor | Ve el pago confirmado en el panel, sin revisar comprobantes. |
| 6 | Cliente | Usa sus puntos como descuento en el siguiente pago. |

## 4. Programa de fidelidad

| Acción del cliente | Premio |
|---|---|
| Primer apartado pagado con FLC | 20 FLC de bienvenida ($20.000) |
| Cargar 500 FLC o más de una vez | 2 % extra en FLC |
| Arriendo pagado a tiempo | 1 % del canon en FLC cada mes (canon de $1.500.000 → 15 FLC) |
| Referir a un nuevo cliente | 50 FLC cuando se cierra el negocio |
| Completar 12 meses de arriendo puntual | 5 % de descuento en el mes 13 |

Los puntos se ganan en FLC y se usan como parte del siguiente pago.

## 5. La moneda física

Como elemento de campaña (actividad FabLab) se imprime en 3D una moneda FELICOIN de 4 cm de diámetro:

- **Anverso:** nombre FELICOIN, casa con cerradura (inmueble apartado y seguro), pistas de circuito y «ONE GOAL · ABITARE».
- **Reverso:** bloques hexagonales encadenados (blockchain), el símbolo ₣ y el eslogan «Tu inmueble, apartado y seguro».

Archivos: `assets/felicoin_llavero_35mm.stl` (un color) y `assets/FELICOIN.3mf` (dos colores).

## 6. Siguientes pasos

1. Validar con la dueña de Abitare el valor de 1 FLC y los premios.
2. Agregar a la página la pantalla de saldo y puntos del cliente.
3. Probar el flujo completo con un inquilino real en red de prueba.

Fuentes de precios: iProUP (BTC y ETH, 2 nov. 2026), CryptoTicker/CoinGecko (ADA, 4 nov. 2026), CoinMarketCap (SUI, 8 nov. 2026), CoinGape (PI, nov. 2026), Portafolio (TRM, 4 nov. 2026).

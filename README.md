# 🏦 Lending Club - Análisis de Datos Histórico

# 📑 Introducción

**Lending Club** es una compañía estadounidense de préstamo entre particulares, con sede en San Francisco, Estados Unidos de América. Fue el primer sitio de préstamo entre particulares en registrar sus productos como valores con la Securities and Exchange Commission (SEC), y ofrecer un servicio de préstamos en el mercado secundario. **Lending Club** es pionera de servicios de préstamos entre particulares.

# 💾 Data Set

La base de datos usada se extrajo directamente desde Kaggle:

**Source:** Lending Club historical loan data (2007–2020)
- [Dataset link](https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1)

A continuación, se describirán las variables más importantes de la base de datos usada para el análisis:

| LoanStatNew | Descripción |
|-------------|-------------|
| **loan_amnt** | El monto listado del préstamo solicitado por el prestatario. Si en algún momento el departamento de crédito reduce el monto, esto se reflejará en este valor. |
| **term** | El número de pagos del préstamo. Los valores están en meses y pueden ser 36 o 60. |
| **int_rate** | Tasa de interés del préstamo. |
| **installment** | Pago mensual que debe realizar el prestatario si el préstamo se otorga. |
| **grade** | Calificación del préstamo asignada por Lending Club (LC). |
| **sub_grade** | Subcalificación del préstamo asignada por LC. |
| **emp_title** | Título del empleo proporcionado por el prestatario al solicitar el préstamo. |
| **emp_length** | Tiempo de empleo en años. Valores posibles de 0 a 10, donde 0 significa menos de un año y 10 significa diez o más años. |
| **home_ownership** | Estado de propiedad de la vivienda proporcionado por el prestatario durante el registro o obtenido del informe crediticio. Valores: RENT (alquila), OWN (propia), MORTGAGE (hipotecada), OTHER (otro). |
| **annual_inc** | Ingreso anual autoinformado por el prestatario durante el registro. |
| **verification_status** | Indica si el ingreso fue verificado por LC, no verificado o si se verificó la fuente del ingreso. |
| **issue_d** | Mes en que se financió el préstamo. |
| **loan_status** | Estado actual del préstamo. |
| **purpose** | Categoría proporcionada por el prestatario para la solicitud del préstamo. |
| **title** | Título del préstamo proporcionado por el prestatario. |
| **zip_code** | Los primeros 3 números del código postal proporcionado por el prestatario en la solicitud del préstamo. |
| **addr_state** | Estado proporcionado por el prestatario en la solicitud del préstamo. |
| **dti** | Ratio calculado como los pagos totales mensuales de deuda del prestatario sobre las obligaciones de deuda totales (excluyendo hipoteca y el préstamo solicitado a LC), dividido por el ingreso mensual autoinformado del prestatario. |
| **earliest_cr_line** | Mes en que se abrió la línea de crédito más antigua reportada del prestatario. |
| **open_acc** | Número de líneas de crédito abiertas en el historial crediticio del prestatario. |
| **pub_rec** | Número de registros públicos negativos (derogatorios). |
| **revol_bal** | Saldo total de crédito revolvente. |
| **revol_util** | Porcentaje de utilización de línea de crédito revolvente, es decir, cuánto crédito está usando el prestatario respecto al total disponible. |
| **total_acc** | Número total de líneas de crédito actualmente en el historial crediticio del prestatario. |
| **initial_list_status** | Estado inicial de listado del préstamo. Posibles valores: W, F. |
| **application_type** | Indica si la solicitud de préstamo es individual o conjunta (dos co-prestatarios). |
| **mort_acc** | Número de cuentas hipotecarias. |
| **pub_rec_bankruptcies** | Número de quiebras registradas en registros públicos. |

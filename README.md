# 20180228_EXAMEN01_024313

JUSTIFICACIÓN

El diagrama anterior funciona muy bien para tratar de realizar transacciones bancarias.
La clase abstracta Bank se extiende a BankA, BankB,BankC.  Como se puede ver, cualquiera de los bancos puede enviar un protocolo que ellos decidan ya sea usb, html y http. El diagrama de la utiliza el patrón de diseño de método de fábrica. Utilice este método porque es más práctico para el problema que se presenta ya que si se desea implementar un protocolo distinto a bancos que se vayan implementando estos puedan tomar ese protocolo.


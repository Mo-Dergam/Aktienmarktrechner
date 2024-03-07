Betrag = float(input("geben Sie den Betrag ein:"))
Jahren = float(input("geben Sie ein auf wie viele Jahren möchten Sie Ihre Rendite Rechnen:"))

if Jahren == 0: 
 print(" Sie haben einen ungültigen wert einegegeben")

elif Jahren == 1:
 Rendite = Betrag * 0.08 * Jahren
 Neu_Betrag = Rendite + Betrag 
 print(f"Ihre Betrag wird in einem Jahr so sein {Neu_Betrag}")

else: 
 Rendite = Betrag * 0.08 * Jahren
 Neu_Betrag = Rendite + Betrag 
 print(f"Ihre Betrag wird in {Jahren} jahren so sein {Neu_Betrag}")

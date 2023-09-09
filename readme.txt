#dzielenie duzego pliku (czesci po 30M)
split -b 30M loanCalculator_03.tgz loanCalculator_03_parts
łączenie
cat loanCalculator_03_parts* > loanCalculator_03.tgz

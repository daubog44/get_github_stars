Per le informazione di utilizzo: aprire il terminale nella cartella dove si trova get_github_stars.exe, scrivere: "./get_github_stars.exe --help".

è consigliabile usare un token dell' api github, per aumentare le richieste possibili al server (5000 all' ora) altrimenti saranno 60 all' ora prima che il server blocchi l' ip, per ottenere il token segui la [guida](https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

il formato del file csv di input deve essere: id,url,company,name

esempio:

```
./get_github_stars.exe --file-csv "percorso\file.csv" --token token_github
```

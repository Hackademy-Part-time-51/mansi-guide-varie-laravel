# Init di un Progetto

## Installazione via Laravel New

1. Con il terminale sottomano, posizionati nella cartella generale dove andrai a mettere tutti i tuoi progetti
2. Lancia il comando `laravel new nome-progetto`
3. Attendi la fine dell’installazione 
4. entra nel progetto appena creato con `cd nome-progetto`
5. Apri Visual studio con `code .`
6. E successivamente `php artisan serve`

## Installazione via Git Clone

1. Vai al link della repository di github: https://github.com/laravel/laravel
2. Apri il pulsante verde **<> Code** e copia il link HTTPS https://github.com/laravel/laravel.git presente nel dropdown
3. Con il terminale sottomano, posizionati nella cartella generale dove andrai a mettere tutti i tuoi progetti
4. Lancia il comando `git clone  https://github.com/laravel/laravel.git nome-progetto`
5. Attendi la fine dell’installazione 
6. Entra nel progetto appena creato con `cd nome-progetto`
7. Apri Visual studio con `code .`
8. Rimuovi il file .git con `rm -fr .git`
9. Lancia il comando `composer install`
10. Successivamente, sempre nel progetto con il terminale aperto, lancia il comando di copia del file .env con `cp .env.example .env`. (Oppure fai copia e incolla dal progetto)
11. Lancia il comando `php artisan key:generate` per generare la chiave
12. E successivamente `php artisan serve`

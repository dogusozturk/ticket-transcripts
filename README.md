# Ticket Transcripts

Desk Officer botunun ticket kayıtları (transcript) için GitHub Pages sitesi.

`t/` klasöründeki her dosya bir ticket'ın **şifrelenmiş** kaydıdır (AES-256-GCM). Repo herkese açık
olsa da içerikler okunamaz: çözme anahtarı yalnızca botun gönderdiği linkin `#` işaretinden sonraki
kısmında bulunur ve tarayıcılar bu kısmı hiçbir sunucuya göndermez. Link açıldığında `index.html`
kaydı okuyucunun tarayıcısında çözer ve gösterir.

Bu repoya elle dosya eklemeye gerek yoktur; bot yeni transcript'leri kendisi yükler.

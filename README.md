<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

Kuyacetyiswa ukuba ufake iinodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) kuqala, kwaye ke `direnv allow` emva kokungena kulawulo ( [i.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) iya kwenziwa ngokuzenzekelayo emva kokungena kulawulo).

Intsingiselo yile: ukuguqulelwa kwesiTshayina kwisiJapan, isiKorea, isiNgesi, ukuguqulelwa kwesiNgesi kuzo zonke ezinye iilwimi. Ukuba ufuna kuphela ukuxhasa isiTshayina kunye nesiNgesi, ungabhala nje `zh: en` .

Intsingiselo yile: ukuguqulelwa kwesiTshayina kwisiJapan, isiKorea, isiNgesi, ukuguqulelwa kwesiNgesi kuzo zonke ezinye iilwimi. Ukuba ufuna kuphela ukuxhasa isiTshayina kunye nesiNgesi, ungabhala nje `zh: en` .

* [ikhowudi yesiphelo](https://github.com/xxai-art/web)
* [Iipakethe zolwimi zesayithi ngokubanzi](https://github.com/xxai-art/web/tree/main/i18n)
* [Iipakethi zolwimi kwiimodyuli zokungena](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Uxwebhu lweWebhusayithi ngeelwimi ezininzi](https://github.com/xxai-doc)

Ulwimi lweprogram yangaphambili ngu [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , eyongeza ezinye iimpawu ezisekelwe kwi-syntax ye-coffeescript, bona [./coffee_plus.md](./coffee_plus.md) .

## Ukwenziwa kwamazwe ngamazwe kweewebhusayithi kunye namaxwebhu

Yakha kwezi projekthi zi-3 zilandelayo

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Isimamva sithi `.mdt` , ungasebenzisa isivakalisi esifana ne `<+ ./coffee_plus/import.js>` ukubhekisa kwiifayile zangaphandle, kwaye wenze uphawulo ngesimamva `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Inguqulelo yeMarkdown ayizukuguqula iikhowudi kunye namakhonkco, kwaye iya kufihla izivakalisi eziguqulelweyo. Ukuba inguqulelo ilungisiwe kodwa umbhalo wokuqala ungalungiswanga, ukuwusebenzisa kwakhona akusayi kuluvala uguqulo lwenguqulelo.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Iifayile zolwimi zokuguqulela iiwebhusayithi eziveliswe `yaml` .

### IMiyalelo yoGuqulelo oluSebenzayo loXwebhu

Jonga ikhowudi yokugcina [xxai-art/doc](https://github.com/xxai-art/doc)

Kuyacetyiswa ukuba ufake iinodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) kuqala, kwaye ke `direnv allow` emva kokungena kulawulo ( [i.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) iya kwenziwa ngokuzenzekelayo emva kokungena kulawulo).

Ukuze ugweme isiseko esikhulu sekhowudi esiguqulelwe kwiilwimi ezingamakhulu, ndenze isiseko sekhowudi eyahlukileyo kulwimi ngalunye kwaye ndenza umbutho wokugcina isiseko sekhowudi.

Ukucwangcisa imo yendalo eguquguqukayo `GITHUB_ACCESS_TOKEN` kwaye emva koko isebenze [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) iya kudala ngokuzenzekelayo indawo yokugcina ikhowudi.

Ngokuqinisekileyo, unokuyibeka kwakhona kwisiseko sekhowudi.

Isalathiso sombhalo wenguqulelo [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Ikhowudi yeskripthi itolikwa ngolu hlobo lulandelayo:

[i-bunx](https://bun.sh/docs/cli/bunx) yindawo ye-npx, ekhawulezayo. Ewe kunjalo, ukuba awunayo i-bun efakiweyo, ungasebenzisa `npx` endaweni yoko.

`bunx mdt zh` renders `.mdt` kuluhlu lwe zh njenge `.md` , bona iifayile ezi-2 ezidityanisiweyo ngezantsi

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` yikhowudi engundoqo yoguqulelo (ukuba une `nodejs` ezifakiweyo kuphela, kodwa `bun` kunye `direnv` ayifakelwanga, ungaqhuba `npx i18n` ukuguqulela).

Iza kwahlula [i-i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , uqwalaselo lwe `i18n.yml` kolu xwebhu ngolu hlobo lulandelayo:

```
en:
zh: ja ko en
```

Intsingiselo yile: ukuguqulelwa kwesiTshayina kwisiJapan, isiKorea, isiNgesi, ukuguqulelwa kwesiNgesi kuzo zonke ezinye iilwimi. Ukuba ufuna kuphela ukuxhasa isiTshayina kunye nesiNgesi, ungabhala nje `zh: en` .

Eyokugqibela ithi [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , ekhupha umxholo phakathi kwesihloko esiyintloko kunye nesihlokwana sokuqala solwimi ngalunye lwe `README.md` ukuvelisa ingeniso `README.md` . Ikhowudi ilula kakhulu, ungayijonga ngokwakho.

I-API kaGoogle isetyenziselwa ukuguqulela simahla. Ukuba awukwazi ukufikelela kuGoogle, nceda uqwalasele kwaye usete ummeli, onje:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Iskripthi sokuguqulela siza kuvelisa i-cache eguqulelweyo kwi `.i18n` directory, nceda uyijonge nge `git status` kwaye uyifake kwindawo yokugcina ikhowudi ukuphepha iinguqulelo eziphindaphindiweyo.

Nceda sebenzisa `bunx i18n` ngalo lonke ixesha ulungisa uguqulelo ukuze uhlaziye i-cache.

Ukuba umbhalo wokuqala kunye noguqulelo luguqulwa ngexesha elifanayo, i-cache iya kubhidaniswa, ngoko ke ukuba ufuna ukuyiguqula, unokuguqula enye kuphela, kwaye emva koko uqhube `bunx i18n` ukuhlaziya i-cache.

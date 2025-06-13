# 💬 xerrAIre: Diàleg Interactiu amb IA (OpenRouter)

![Llicència](https://img.shields.io/badge/Llic%C3%A8ncia-MIT-green.svg) ![Estat](https://img.shields.io/badge/Estat-Funcional%20(Beta)-blue.svg) ![Versió](https://img.shields.io/badge/Versi%C3%B3-1.0-yellow.svg)

Benvingut/da a xerrAIre, una aplicació web portable dissenyada perquè puguis conversar amb models avançats d'intel·ligència artificial directament des del teu navegador, utilitzant la potència d'OpenRouter.ai. Formula preguntes, explora idees, interromp, reprèn punts anteriors i descarrega les teves converses en un format clar i simple.

---

## 🚀 Prova'l Ara Online! 🚀

No cal instal·lar res. Pots començar a explorar el món de la conversa intel·ligent a l'instant.

> ### [Accedeix a xerrAIre Online Fent Clic Aquí](https://xesco-tejedor.github.io/xerrAIre/)

---

<!-- ![dialogo-ai](/assets/dialogo-ai-placeholder.png) -->
<!-- (Opcional: Afegeix aquí una captura de pantalla de l'aplicació.
    He posat un placeholder. Si la guardes en una carpeta 'assets', ajusta la ruta.) -->

## ✨ Característiques Principals

*   🗣️ **Interacció Fluida amb IA:** Conversa de forma escrita amb models de llenguatge avançats a través de l'API d'OpenRouter.
*   🔑 **Configuració Senzilla d'API:** Introdueix la teva API Key d'OpenRouter i selecciona el teu model preferit de la llista d'opcions gratuïtes.
*   🧠 **Personalització de la IA:** Defineix el comportament de la IA amb un "System Prompt" i ajusta la quantitat d'historial que s'envia com a context.
*   📜 **Historial de Conversa:** Tots els teus diàlegs es guarden automàticament al LocalStorage del teu navegador (associat a la ruta de l'arxiu o l'URL de l'aplicació).
*   ↪️ **Reprendre Punts Anteriors:** Fes clic a qualsevol missatge teu anterior per copiar el seu contingut a l'àrea de text i continuar des d'allà.
*   💾 **Exportació a Markdown:** Descarrega l'historial complet de la conversa, incloent-hi el System Prompt utilitzat, en un arxiu `.md` ben formatat.
*   🔌 **Portabilitat (Versió Local):** Si descarregues l'arxiu HTML, pots dur-lo en un USB i usar-lo en qualsevol ordinador amb navegador.
*   🔒 **Privacitat:** La teva API Key d'OpenRouter s'utilitza directament per a les trucades a l'API i **no s'emmagatzema permanentment** al LocalStorage per defecte per a major seguretat (s'introdueix per sessió).

## 🔧 Ús i Configuració

1.  **Accedir a l'Aplicació:**
    *   Fes clic a l'enllaç: **[xerrAIre Online](https://xesco-tejedor.github.io/xerrAIre/)**
    *   O, si prefereixes executar-la localment, descarrega l'arxiu `index.html` (o el nom que tingui el teu fitxer principal) i obre'l amb el teu navegador web.

2.  **Obtenir i Configurar una Clau API d'OpenRouter.ai (MOLT IMPORTANT!):**
    *   Perquè la IA respongui, necessites la teva pròpia clau API d'OpenRouter.
    *   Ves a **[OpenRouter.ai](https://openrouter.ai/keys)**.
    *   Registra't (si encara no ho has fet) i crea una nova clau API. OpenRouter ofereix accés a diversos models, alguns amb capes gratuïtes generoses o crèdits inicials.
    *   A l'aplicació xerrAIre, ves a la columna "Configuració d'IA".
    *   **Enganxa la teva clau API** al camp "API Key (OpenRouter)".
    *   **Selecciona un model** de la llista desplegable.
    *   Opcionalment, modifica el **System Prompt** per donar-li una personalitat o instruccions específiques a la IA.
    *   Ajusta quants **missatges d'historial** s'envien per donar context a la IA.

3.  **A Xerrar!**
    *   Escriu el teu missatge a l'àrea de text principal i prem "Enviar" o la tecla Enter.

## 🗺️ Full de Ruta i Millores Futures

Aquest projecte és una eina útil que pot continuar creixent.

> #### ⚠️ Millores Actuals en Ment
> *   **Optimització del Context:** Explorar formes més eficients de gestionar l'historial enviat a l'API per a converses llargues.
> *   **Gestió d'Errors Avançada:** Proveir retroalimentació més detallada sobre errors específics de l'API o dels models.

> #### 💡 Pròximes Característiques (Possibles)
> *   Opció per desar l'API Key al LocalStorage (amb una advertència de seguretat clara).
> *   Actualització dinàmica de la llista de models des d'OpenRouter (si és factible sense backend).
> *   Possibilitat d'editar/esborrar missatges individuals de l'historial.
> *   Selector de temes (clar/fosc).
> *   Suport per a respostes en *streaming* (si els models gratuïts d'OpenRouter i la simplicitat del frontend ho permeten).

## 🚀 Tecnologies Utilitzades

*   💻 **HTML5**
*   🎨 **CSS3 (Estils en línia i bàsics)**
*   🤖 **JavaScript (Vanilla ES6+)**
*   🧠 **API d'OpenRouter.ai** (per a la interacció amb LLMs)
*   💾 **LocalStorage del Navegador** (per a l'historial del xat)

## 🙌 Com Contribuir

Les contribucions, idees i informes d'errors són benvinguts. Si tens algun suggeriment per millorar l'aplicació:
*   Obre una **Issue** al repositori del projecte: [xesco-tejedor/xerrAIre/issues](https://github.com/xesco-tejedor/xerrAIre/issues) (si el repositori existeix amb aquest nom).
*   Envia una **Pull Request** si vols aportar codi directament.

## 📄 Llicència

Aquest projecte està sota la **Llicència MIT**. Sent-te lliure d'usar-lo, modificar-lo i distribuir-lo segons els termes de la llicència.

---
_Conversa, experimenta i aprèn._

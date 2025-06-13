# 💬 Diàleg Interactiu amb IA (OpenRouter)

![Llicència](https://img.shields.io/badge/Llic%C3%A8ncia-MIT-green.svg) ![Estat](https://img.shields.io/badge/Estat-Funcional%20(Beta)-blue.svg) ![Versió](https://img.shields.io/badge/Versi%C3%B3-1.0-yellow.svg)

Benvingut/da a Diàleg Interactiu amb IA, una aplicació web portable dissenyada perquè puguis conversar amb models avançats d'intel·ligència artificial directament des del teu navegador, utilitzant la potència d'OpenRouter.ai. Formula preguntes, explora idees, interromp, reprèn punts anteriors i descarrega les teves converses en un format clar i simple.

---

## 🚀 Com Utilitzar-ho Directament 🚀

Aquesta aplicació és un **únic arxiu HTML**. No necessites instal·lar res.

1.  **Descarrega** l'arxiu `dialogo_openrouter.html`.
2.  **Copia'l** a la teva memòria USB o desa'l al teu ordinador.
3.  **Obre'l** amb qualsevol navegador web modern (Chrome, Firefox, Edge, Safari).
4.  Comença a dialogar!

*(No requereix un servidor web per funcionar localment.)*

---

<!-- ![dialogo-ai](/assets/dialogo-ai-placeholder.png) -->
<!-- (Opcional: Afegeix aquí una captura de pantalla de l'aplicació quan la tinguis.
    He posat un marcador de posició. Si la deses a una carpeta 'assets', ajusta la ruta.) -->

## ✨ Característiques Principals

*   🗣️ **Interacció Fluida amb IA:** Conversa de forma escrita amb models de llenguatge avançats a través de l'API d'OpenRouter.
*   🔑 **Configuració Senzilla d'API:** Introdueix la teva API Key d'OpenRouter i selecciona el teu model preferit de la llista d'opcions gratuïtes.
*   🧠 **Personalització de la IA:** Defineix el comportament de la IA amb un "System Prompt" i ajusta la quantitat d'historial que s'envia com a context.
*   📜 **Historial de Conversa:** Tots els teus diàlegs es desen automàticament al LocalStorage del teu navegador (associat a la ruta de l'arxiu).
*   ↪️ **Reprendre Punts Anteriors:** Fes clic a qualsevol missatge teu anterior per copiar el seu contingut a l'àrea de text i continuar des d'allà.
*   💾 **Exportació a Markdown:** Descarrega l'historial complet de la conversa, incloent-hi el System Prompt utilitzat, en un arxiu `.md` ben formatat.
*   🔌 **Portabilitat USB:** Porta-la amb tu en un USB i fes-la servir a qualsevol ordinador amb navegador.
*   🔒 **Privacitat:** La teva API Key d'OpenRouter s'utilitza directament per a les crides a l'API i **no es desa permanentment** al LocalStorage per defecte per a més seguretat (s'introdueix per sessió).

## 🔧 Configuració i Ús

1.  **Descarregar l'Arxiu:**
    *   Simplement desa el codi proporcionat com a `dialogo_openrouter.html`.

2.  **Obrir al Navegador:**
    *   Localitza l'arxiu `dialogo_openrouter.html` i obre'l amb el teu navegador web.

3.  **Obtenir i Configurar una Clau API d'OpenRouter.ai (MOLT IMPORTANT!):**
    *   Perquè la IA respongui, necessites la teva pròpia clau API d'OpenRouter.
    *   Ves a **[OpenRouter.ai](https://openrouter.ai/keys)**.
    *   Registra't (si encara no ho has fet) i crea una nova clau API. OpenRouter ofereix accés a diversos models, alguns amb capes gratuïtes generoses o crèdits inicials.
    *   A l'aplicació, ves a la columna "Configuració d'IA".
    *   **Enganxa la teva clau API** al camp "API Key (OpenRouter)".
    *   **Selecciona un model** de la llista desplegable.
    *   Opcionalment, modifica el **System Prompt** per donar-li una personalitat o instruccions específiques a la IA.
    *   Ajusta quants **missatges d'historial** s'envien per donar context a la IA.

4.  **A Xatejar!**
    *   Escriu el teu missatge a l'àrea de text principal i prem "Enviar" o la tecla Enter.

## 🗺️ Full de Ruta i Millores Futures

Aquest projecte és una eina útil que pot continuar creixent.

> #### ⚠️ Millores Actuals en Ment
> *   **Optimització del Context:** Explorar formes més eficients de gestionar l'historial enviat a l'API per a converses llargues.
> *   **Gestió d'Errors Avançada:** Proveir retroalimentació més detallada sobre errors específics de l'API o dels models.

> #### 💡 Pròximes Característiques (Possibles)
> *   Opció per desar la API Key al LocalStorage (amb una advertència de seguretat clara).
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

Les contribucions, idees i informes d'errors són benvinguts. Si tens algun suggeriment per millorar l'aplicació, no dubtis a:
*   Obrir una **Issue** al repositori del projecte (si n'existís un de públic).
*   Contactar directament si és un projecte personal.

## 📄 Llicència

Aquest projecte està sota la **Llicència MIT**. Sentiu-vos lliures d'utilitzar-lo, modificar-lo i distribuir-lo segons els termes de la llicència.

---
_Conversa, experimenta i aprèn._
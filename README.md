# Readme

## Español:

### Proyecto de difusión de sentimientos en la red corporativa Enron

Este proyecto analiza la propagación de sentimientos negativos dentro de la red de correos electrónicos de Enron, una de las mayores empresas energéticas de EE.UU., cuya quiebra en 2001 se convirtió en uno de los escándalos financieros más impactantes de la historia.

La base de datos utilizada en este estudio está disponible en múltiples fuentes, como la Biblioteca del Congreso de los Estados Unidos (ver https://www.loc.gov/item/2018487913/).

Tras el colapso de la empresa, el gobierno estadounidense obtuvo acceso a los correos electrónicos intercambiados entre sus empleados. Luego de analizarlos, se decidió liberar esta información para fines educativos y de investigación.

### Objetivo del proyecto

El objetivo central es identificar la difusión de sentimientos negativos dentro de la red corporativa, entendidos como aquellos mensajes cuyo contenido léxico negativo supera un umbral determinado. Un empleado puede “infectarse” de preocupación debido a la exposición a malas noticias sobre la empresa a través de los correos electrónicos enviados por sus compañeros.

Dado que la propagación de sentimientos no es un contagio simple, sino un fenómeno de contagio complejo que generalmente requiere influencia social, este proyecto busca analizar el papel de la interacción entre empleados en la difusión del pesimismo y la incertidumbre.

El archivo principal, Enron_Email.ipynb, se centra en evaluar la influencia social que recibe un empleado en el momento en que comienza a mostrar preocupación en sus correos electrónicos.

Los resultados revelan que una fracción significativa de empleados superó el umbral de contenido negativo sin haber recibido previamente correos con carga emocional negativa de sus compañeros. Esto sugiere que la transmisión del sentimiento negativo no se limitó únicamente a los correos electrónicos, sino que también pudo haberse producido a través de otros canales, como conversaciones informales en los pasillos de la empresa.

### Aspectos técnicos

Este proyecto enfrenta y resuelve varias dificultades técnicas, incluyendo:
	•	Identificación individual de los correos electrónicos, asegurando que cada mensaje se asocie correctamente con su remitente y destinatarios.
	•	Unificación de los formatos de fecha, ya que la base de datos de Enron contiene múltiples formatos temporales que requieren estandarización.
	•	Manejo eficiente de los cuerpos de los mensajes, asegurando una representación adecuada del contenido textual para su análisis.

El análisis ha sido desarrollado íntegramente en Python, y el script principal es Enron_Email.ipynb.

⸻

## English:

### Sentiment Diffusion in the Enron Corporate Network

This project analyzes the spread of negative sentiment within Enron’s corporate email network. Enron, once one of the largest energy companies in the U.S., collapsed in 2001 in one of the most infamous financial scandals in history.

The dataset used in this study is publicly available through multiple sources, including the U.S. Library of Congress (see https://www.loc.gov/item/2018487913/).

Following Enron’s collapse, the U.S. government gained access to internal emails exchanged among employees. After conducting an initial analysis, it was decided to release this data for educational and research purposes.

### Project Objective

The primary goal is to identify the spread of negative sentiment within Enron’s corporate network, focusing on messages where the lexical content surpasses a predefined negativity threshold. An employee may become “infected” with concern over the company’s downfall through exposure to emails containing negative information.

Since sentiment diffusion is a complex contagion—typically requiring social reinforcement—this project examines the role of peer influence in spreading pessimism and uncertainty.

The core analysis, conducted in Enron_Email.ipynb, investigates the social influence an employee receives at the moment they begin expressing concern in their emails.

The results indicate that a significant fraction of employees exhibited high levels of negative sentiment without prior exposure to negative emails from colleagues. This suggests that the spread of pessimistic sentiment was not exclusively email-driven but likely reinforced by other communication channels, such as in-person office conversations.

### Technical Considerations

This project addresses and resolves several technical challenges, including:
	•	Unique identification of emails, ensuring that each message is correctly attributed to senders and recipients.
	•	Standardization of date formats, as Enron’s dataset contains multiple time formats that required harmonization.
	•	Efficient processing of email bodies, ensuring proper text representation for sentiment analysis.

The entire analysis is implemented in Python, with Enron_Email.ipynb as the main script.

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/aoliveram/Enron-Email-Analysis">Enron-Email-Analysis</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="http://aoliveram.cl">Anibal Olivera M</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
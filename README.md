<docbook>SRS(Спецификация требований ПО)</docbook>

Шаблон Спецификации требований программного обеспечения, соответствующий стандарту IEEE Std 830-1998 (см. IEEE 12207) 
в формате Docbook 5.
This is template of SRS document which correspond to IEEE Std 830-1998 (ref IEEE 12207) in DocBook 5 format.

-Описание-
./template/ - содержит шаблон для SRS
├── graphics - картинки и.т.д.
│   └── company_logo.png
├── includes - главы и прочие включения и.т.д.
│   ├── introduction.xml
│   ├── overall_description.xml
│   └── specific_requirements.xml
├── names.entities - переменные для подстановки
├── settings - настройки для author xml (конфиги FOP'а и готовый сценарий для трансформации в PDF)
│   ├── fop-config.xml
│   └── srs_scenario.scenarios
└── srs.xml - основной документ

-Лицензия-
Все материалы распространяются на условиях лицензии [Creative Commons BY-SA 3.0] http://creativecommons.org/licenses/by-sa/3.0/deed.ru
Полный текст лиценции находится в файле COPYING


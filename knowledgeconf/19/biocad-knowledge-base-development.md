# Разработка базы знаний компании, которй действительно пользуются

Екатерина Гудкова, Биокад

# Исходные данные

* биотехнологическая компания, 50% - R&D
* необходимо одно место для хранения и переиспользования знаний

# Проблемные зоны при построении базы знаний

* с точки зрения системы - масштабируемость, соответствие стандартам, структура данных, безопасный доступ
* с точки зрения человека - любознательность, ответственность, саморазвитие, осознанность

# Подход к построению базы знаний

* отталкиваются от набора ролей и компетенций - роли, типовые задачи, компетенции, материалы базы знаний
* в каждой команде есть HR-специалист + специалист операционного менеджмента, они собирают данные, которые уходят в ИТ-отдел
* для новых сотрудников
  * индивидуальный план обучения строится под роли
  * FAQ-бот для часто встречающихся вопросов, вытащили поисковые запросы из портала и добавили в бот, топ-5 - работа с системами, оформление командировки, льготы и компенсации, ролевая модель, глоссарий
* для опытных сотрудников
  * нужно узнавать о новостях области, о коллегах 
  * для каждой роли прописали теги, по текстам строят графовую репрезентацию, используют для поиска, в том числе аномальных связей
  * информация приходит в новостной бот, есть обязательные теги, на которые подписаны сотрудники, есть рекомендуемые (Universal recommender, открытое ПО)

#Проект qa_guru_13_05052024
qa_guru_13_05052024

Лекция_3, урок Github

Строчка была добавлена из PyCharm


browser.open('https://school.qa.guru')
browser.element('[name="email"]').type('alma.bekbergenova@tele2.kz').press_enter()
browser.element('[name="password"]').type('+5x++b++Y').press_enter().press_enter()
browser.element('[class="page-header"]').should(have.text('Список тренингов'))

browser.open('https://school.qa.guru/cms/system/login')
browser.element('[class="logined-form"]').should(have.text('Здравствуйте, Алма'))


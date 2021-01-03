# goit-markup-hw-05

#GOIT Домашка №5

#This site is published at https://zlukaprapor.github.io/goit-markup-hw-05/

Свойство transition задаем для базового состояния элемента (а не для состояния ховера/фокуса).
Явно указываем анимируемое свойство (transition-property). Да-да, знаем: куда легче написать all или не прописать transition-property вовсе (all применится по умолчанию). Но сделайте приятное ментору: не поленитесь указать нужное transition-property, это нужно прежде всего для вашей же тренировки и закрепления знаний.
Анимируем переходы для ВСЕХ элементов, для которых стилизированы состояния ховера/фокуса.

Для всех эффектов ховера и фокуса сделаны переходы. Время - 250ms, функция распределения времени - cubic-bezier(0.4, 0, 0.2, 1).
В секции Портфолио, синий оверлей с текстом поверх изображения выезжает снизу изображения, как показано на видео ниже.

Появление и скрытие модального окна анимированы при помощи перехода с произвольным эффектом, например scale или translate, и opacity.

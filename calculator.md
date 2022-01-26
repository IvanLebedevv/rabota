{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "7ad34281",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Выберите операцию: +, -, *, /, **/\n",
      "Введите первое число: 6\n",
      "Введите второе число: 2\n",
      "Ответ: 3.0\n"
     ]
    }
   ],
   "source": [
    "calc = input('Выберите операцию: +, -, *, /, **')\n",
    "if calc == \"+\":\n",
    "    a = float(input('Введите первое число: '))\n",
    "    b = float(input('Введите второе число: '))\n",
    "    c = a + b\n",
    "    print('Ответ: ' + str(c))\n",
    "\n",
    "elif calc == '-':\n",
    "    a = float(input('Введите первое число: '))\n",
    "    b = float(input('Введите второе число: '))\n",
    "    c = a - b\n",
    "    print('Ответ: ' + str(c))\n",
    "    \n",
    "elif calc == '*':\n",
    "    a = float(input('Введите первое число: '))\n",
    "    b = float(input('Введите второе число: '))\n",
    "    c = a * b\n",
    "    print('Ответ: '  + str(c))\n",
    "    \n",
    "elif calc == '/':\n",
    "    a = float(input('Введите первое число: '))\n",
    "    b = float(input('Введите второе число: '))\n",
    "    c = a / b\n",
    "    print('Ответ: '  + str(c))\n",
    "    \n",
    "elif calc == '**':\n",
    "    a = float(input('Введите первое число: '))\n",
    "    b = float(input('Введите второе число: '))\n",
    "    c = a ** b\n",
    "    print('Ответ: ' + str(c))\n",
    "    \n",
    "else:\n",
    "    print(\"Выбрана неверная операция\")\n",
    "\n",
    "    input()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "bcbb5f71",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

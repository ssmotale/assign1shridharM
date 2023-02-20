{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "06b01c96-8b70-47c0-852c-753596e8adbf",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 9,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q1. What are the characteristics of the tuples? Is tuple immutable?\n",
    "ans: tuple is immmutable\n",
    "\"\"\"\n",
    "\"\"\"\n",
    "Q2. What are the two tuple methods in python? Give an example of each method. Give a reason why\n",
    "tuples have only two in-built methods as compared to Lists.\n",
    "\n",
    "ans: count and index are the two methodes used in tuples, \n",
    "\n",
    "Reason:As tuple is immutable hence we cant change elements inside tuple once assigned.therefore only 2 methodes \n",
    "compared to list which is mutable\n",
    "\n",
    "\"\"\"\n",
    "t1=(1,2,2,34,5,55,5)\n",
    "t1.count(2)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "464584d6-79eb-47d2-9191-2e08520a9195",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 10,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t1=(1,2,2,34,5,55,5)\n",
    "t1.count(2)\n",
    "#output=2"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "id": "e9599d44-eff0-4589-a418-a1f432d12892",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "1"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "t1=(1,2,2,34,5,55,5)\n",
    "x = t1.index(2)\n",
    "x\n",
    "#out=1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "id": "354f567b-302b-44a5-bfca-cfef5528c4c2",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "140446792412608"
      ]
     },
     "execution_count": 34,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q3. Which collection datatypes in python do not allow duplicate items? Write a code using a set to remove\n",
    "duplicates from the given list.\n",
    "Ans: set datatype  allow only unique values \n",
    "\"\"\"\n",
    "List = [1, 1, 1, 2, 1, 3, 1, 4, 2, 1, 2, 2, 2, 3, 2, 4, 3, 1, 3, 2, 3, 3, 3, 4, 4, 1, 4, 2, 4, 3, 4, 4]\n",
    "a=set(List)\n",
    "a\n",
    "id(a)\n",
    "#output:{1, 2, 3, 4}"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "id": "dcfe67d8-b20c-4ae0-873d-1f308c50937a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "94056578422720"
      ]
     },
     "execution_count": 33,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q4. Explain the difference between the union() and update() methods for a set. Give an example of\n",
    "each method.\n",
    "\n",
    "\"\"\"\n",
    "b={5,6,7}\n",
    "c=a.union(b)\n",
    "#id(c)\n",
    "#out:140446792412608\n",
    "d=a.update(b)\n",
    "id(d)\n",
    "#out:94056578422720\n",
    "\n",
    "\n",
    "#output:{1, 2, 3, 4, 5, 6, 7}\n",
    "#update gives updated set at same memory location\n",
    "#union create new memory  location althrough both gives same output"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "id": "368dd83a-ee6b-4795-8eb1-70b6f9c9b086",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'\\nQ5. What is a dictionary? Give an example. Also, state whether a dictionary is ordered or unordered.\\n\\nAns: It is collection of key and value pairs\\nEX.\\ndict1={\"key1\":\"value1\",\"key2\":\"vaalue2\"....\"keyn\":\"valuen\"}\\n\\nDictionaries are ordered\\n'"
      ]
     },
     "execution_count": 35,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q5. What is a dictionary? Give an example. Also, state whether a dictionary is ordered or unordered.\n",
    "\n",
    "Ans: It is collection of key and value pairs\n",
    "EX.\n",
    "dict1={\"key1\":\"value1\",\"key2\":\"vaalue2\"....\"keyn\":\"valuen\"}\n",
    "\n",
    "Dictionaries are ordered\n",
    "\"\"\"\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "id": "2c9527a2-cdd1-4718-8fe0-ac90b78f958b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "{'ram': {'sham': 'sam', 'aam': 'lam'}, 'd': 'f'}"
      ]
     },
     "execution_count": 44,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q6. Can we create a nested dictionary? If so, please give an example by creating a simple one-level\n",
    "nested dictionary.\n",
    " yes it is possible to create nested dictionary\n",
    "\"\"\"\n",
    "d2={\"ram\":{\"sham\":\"sam\",\"aam\":\"lam\"},\"d\":\"f\"}\n",
    "d2\n",
    "#output:{'ram': {'sham': 'sam', 'aam': 'lam'}, 'd': 'f'}"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 62,
   "id": "ea44c1bc-5191-4c34-8e9d-a98fcca383c7",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "list['Python', 'Machine Learning', 'Deep Learning']"
      ]
     },
     "execution_count": 62,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q7. Using setdefault() method, create key named topics in the given dictionary and also add the value of\n",
    "the key as this list ['Python', 'Machine Learning’, 'Deep Learning']\n",
    "\n",
    "\"\"\"\n",
    "list3={\"topic1\":'Python',\"topic2\":\"Machine Learning\",\"topic3\":\"Deep Learning\"}\n",
    "dt1=list3.setdefault(\"topic1\")\n",
    "dt2=list3.setdefault(\"topic2\")\n",
    "dt3=list3.setdefault(\"topic3\")\n",
    "list[dt1,dt2,dt3]\n",
    "#output:list['Python', 'Machine Learning', 'Deep Learning']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 67,
   "id": "4741b070-3faa-4695-b246-8c79e7497dae",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "\"\\nout:dict_items([('Sport', 'Cricket'), ('Teams', ['India', 'Australia', \\n'England', 'South Africa', 'Sri Lanka', 'New Zealand'])])\\n\\n\""
      ]
     },
     "execution_count": 67,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\"\"\"\n",
    "Q8. What are the three view objects in dictionaries? Use the three in-built methods in python to display\n",
    "these three view objects for the given dictionary.\n",
    "\n",
    "Ans:3 views are,1)Key,2)value,3)items\n",
    "\n",
    "\"\"\"\n",
    "dict1 = {'Sport': 'Cricket' , 'Teams': ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand']}\n",
    "dict1.keys()\n",
    "#out:dict_keys(['Sport', 'Teams'])\n",
    "dict1.values()\n",
    "#out:dict_values(['Cricket', ['India', 'Australia', 'England', 'South Africa', 'Sri Lanka', 'New Zealand']])\n",
    "dict1.items()\n",
    "\"\"\"\n",
    "out:dict_items([('Sport', 'Cricket'), ('Teams', ['India', 'Australia', \n",
    "'England', 'South Africa', 'Sri Lanka', 'New Zealand'])])\n",
    "\n",
    "\"\"\"\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "925ceb09-f3fc-4a0f-9ab7-57b091b1d6df",
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
   "version": "3.10.8"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

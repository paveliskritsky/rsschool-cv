# Pavel Iskritsky
## Contacts:
* Item 1 Email : paveliskritsky@yandex.by
* Item 2 Phone number : +375339001200
* Item 3 GitHub :[paveliskritsky](https://github.com/paveliskritsky)
## About me:
I have experience in the field of security.(Access Control System,Fire alarm,security alarm). I have been working in this field for about 2 years. No web development experience. I want to try myself in this area. I'm very interested to figure out how all this works. I took a few courses at HTML Academy. I understand that my knowledge is superficial. I will do my best to become better in this area. I studied as a programmer engineer in Belarusian State Technological University. After passing the first session, I took the documents. Studied C ++. 
## Example code: 
<pre> include &#60;iostream&#62;
    #include &#60;iomanip&#62;
    using namespace std;
    void bubbleSort(int *, int);
    int main(int argc, char* argv[])
    {
        setlocale(LC_ALL, "rus");
        cout << "Введите размер массива: ";
        int size_array; 
        cin >> size_array;
        int *sorted_array = new int [size_array];
        for (int counter = 0; counter < size_array; counter++)
        {
            sorted_array[counter] = rand() % 100; 
            cout << setw(2) << sorted_array[counter] << "  "; 
        }
        cout << "\n\n";
        bubbleSort(sorted_array, size_array); 
        for (int counter = 0; counter < size_array; counter++)
        {
            cout << setw(2) << sorted_array[counter] << "  "; /
        }
        cout << "\n";
        system("pause");
        return 0;
    }
    void bubbleSort(int* arrayPtr, int length_array) 
    {
    int temp = 0; 
    bool exit = false; 
    while (!exit)
    {
    exit = true;
    for (int int_counter = 0; int_counter < (length_array - 1); int_counter++)
        if (arrayPtr[int_counter] > arrayPtr[int_counter + 1]) 
        {
        temp = arrayPtr[int_counter];
        arrayPtr[int_counter] = arrayPtr[int_counter + 1];
        arrayPtr[int_counter + 1] = temp;
        exit = false; 
        }
    }
    }
</pre>
## Skills:
* Item 1 HTML.
* Item 2 CSS.
* Item 3 base C++ 

## Education:
Belarusian National Technical University. Power engineering (20013-2017).
## English level:
A2

# Algoritms-HW-1-14.10.24



let arr = [5, 8, 10, 12, -9, 10, 11, -3];

function bubbleSort(array) {
    let n = array.length;
    for (let i = 0; i < n - 1; i++) {
        for (let j = 0; j < n - 1 - i; j++) {
            if (array[j] > array[j + 1]) {
                let temp = array[j];
                array[j] = array[j + 1];
                array[j + 1] = temp;
            }
        }
    }
}

bubbleSort(arr);

console.log(arr);

// ДЗ из слайда 40 // 

let num1 = parseInt(prompt("Введите первое число:"));
let num2 = parseInt(prompt("Введите второе число:"));
let num3 = parseInt(prompt("Введите третье число:"));

let sum;

sum = num1 + num2 + num3;

console.log("Сумма трех чисел:", sum);

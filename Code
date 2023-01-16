using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace CalculatorApp
{
    /// <summary>
    /// Interaction logic for MainWindow.xaml
    /// </summary>
    public partial class MainWindow : Window
    {
        string input = string.Empty;
        string op1 = string.Empty;
        string op2 = string.Empty;
        char op;
        double result = 0.0;

        public MainWindow()
        {
            InitializeComponent();
        }

        private void Zero_Click(object sender, EventArgs e)
        {
            this.Screen.Text = "";
            input += "0";
            this.Screen.Text += input;
        }

        private void One_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "1";
            this.Screen.Text += input;
        }

        private void Two_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "2";
            this.Screen.Text += input;
        }

        private void Three_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "3";
            this.Screen.Text += input;
        }

        private void Four_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "4";
            this.Screen.Text += input;
        }

        private void Five_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "5";
            this.Screen.Text += input;
        }

        private void Six_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "6";
            this.Screen.Text += input;
        }

        private void Seven_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "7";
            this.Screen.Text += input;
        }

        private void Eight_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "8";
            this.Screen.Text += input;
        }

        private void Nine_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += "9";
            this.Screen.Text += input;
        }

        private void Dot_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            input += ".";
            this.Screen.Text += input;
        }

        private void Modulo_Click(object sender, RoutedEventArgs e)
        {
            op1 = input;
            op = '%';
            input = string.Empty;
        }

        private void Divide_Click(object sender, RoutedEventArgs e)
        {
            op1 = input;
            op = '/';
            input = string.Empty;
        }

        private void Times_Click(object sender, RoutedEventArgs e)
        {
            op1 = input;
            op = '*';
            input = string.Empty;
        }

        private void Minus_Click(object sender, RoutedEventArgs e)
        {
            op1 = input;
            op = '-';
            input = string.Empty;
        }

        private void Plus_Click(object sender, RoutedEventArgs e)
        {
            op1 = input;
            op = '+';
            input = string.Empty;
        }

        private void Clear_Click(object sender, RoutedEventArgs e)
        {
            this.Screen.Text = "";
            this.input = string.Empty;
            this.op1 = string.Empty;
            this.op2 = string.Empty;
        }

        private void Equal_Click(object sender, RoutedEventArgs e)
        {
            op2 = input;
            double num1, num2;
            double.TryParse(op1, out num1);
            double.TryParse(op2, out num2);
            if (op == '+')
            {
                result = num1 + num2;
                Screen.Text = result.ToString();
            }
            else if (op == '-')
            {
                result = num1 - num2;
                Screen.Text = result.ToString();
            }
            else if (op == '*')
            {
                result = num1 * num2;
                Screen.Text = result.ToString();
            }
            else if (op == '/')
            {
                if (num2 != 0)
                {
                    result = num1 / num2;
                    Screen.Text = result.ToString();
                }
                else
                {
                    Screen.Text = "DIV/Zero!";
                }

            }
            else if (op == '%')
            {
                if (num2 != 0)
                {
                    result = num1 % num2;
                    Screen.Text = result.ToString();
                }
                else
                {
                    Screen.Text = "MOD/Zero!";
                }

            }
        }
    }
}

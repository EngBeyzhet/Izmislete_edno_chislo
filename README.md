# Izmislete_edno_chislo
Ние ще ви кажем кое число сте измислили. (Do-while цикли) 

        {
        Console.Write("Намисли си едно число от 1 до 10.");
        var chislo = Console.ReadLine();
        Console.Write("Умножи го по 3.");
        var umnojenotoPoTri = Console.ReadLine();
        Console.Write("Към резултата добави 1.");
        var dobavenotoEdno = Console.ReadLine();
        Console.Write("Умножи полученото число по 3.");
        var umnojenotoPakPoTri = Console.ReadLine();
        Console.Write("Към резултата добави числото, което се измислил.");
        var dobavenotoChislo = Console.ReadLine();
        Console.Write("Въведи числото, което си получил: ");
        int vavedenotoChislo = int.Parse(Console.ReadLine());
        vavedenotoChislo = (vavedenotoChislo / 10) % 10;
        Console.WriteLine("Числото, което си измислил е: " + vavedenotoChislo);
        if (vavedenotoChislo<100)
	{Console.WriteLine("Error");}
        }

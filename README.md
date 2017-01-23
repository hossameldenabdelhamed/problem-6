 int x = 0;
            int y = 0;
            for (int i = 0; i <= 100; i++)
            {
                int ii = i * i;
                x += ii;
            }
            for (int i = 0; i <= 100; i++)
            {
                y += i;
            }
            y = y * y;
            Console.WriteLine("res" + (y - x));

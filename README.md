
#include <stdio.h>

int
main ()
{
  int days;
  scanf ("%d", &days);
  switch (days)
	{
	case 1:
	  printf ("mon");
	  break;
	case 2:
	  printf ("tues");
	  break;
	case 3:
	  printf ("wednes");
	  break;
	case 4:
	  printf ("thrus");
	  break;
	case 5:
	  printf ("fri");
	  break;
	case 6:
	  printf ("satur");
	  break;
	case 7:
	  printf ("sun");
	  break;
	default:
	  printf ("invalid");
	  break;
	}
  return 0;
}

```javascript
import SoftwareDeveloper from 'bagustilas';
import { Languages, Frameworks } from 'bagustilas/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Bagus Tilas Hidayatullah';
  title    = 'Software Developer';
  location = 'Pekalongan, IDN';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'PHP', ...Languages];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['React', 'Next.js', 'Laravel', 'CI', ...Frameworks];
}

```

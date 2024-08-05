## Hi there 👋

import SoftwareDeveloper from 'bagustilas';
import { Languages, Frameworks } from 'bagustilas/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Bagus Tilas Hidayatullah';
  title    = 'Software Developer';
  location = 'Pekalongan, IDN';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'PHP', ...Languages];
  databases  = ['MySQL', 'Supabase', 'Firebase'];
  frameworks = ['CI', 'React', 'Next.js', 'Laravel', ...Frameworks];
}

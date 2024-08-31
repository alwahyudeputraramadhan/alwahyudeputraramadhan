- 👋 Hi, I’m @alwahyudeputraramadhan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
alwahyudeputraramadhan/alwahyudeputraramadhan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->// Import library yang diperlukan
import android.app.Activity;
import android.os.Bundle;
import android.widget.Toast;

// Buat kelas aplikasi mod
public class ModApp extends Activity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Tambahkan kode modifikasi disini
        Toast.makeText(this, "Aplikasi mod telah diaktifkan!", Toast.LENGTH_SHORT).show();
    }
}

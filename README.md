private bool validarcampos()
        {
            bool ok = true;
            if (textclaveauditor.Text == "")
            {
                ok = false;
                errorProvider1.SetError(textclaveauditor, "El Campo no puede estar vacío");
            }
            if (textnomauditor.Text == "")
            {
                ok = false;
                errorProvider1.SetError(textnomauditor, "El Campo no puede estar vacío");
            }
            if (dropubicacion.Text == "" || dropubicacion.Text == "SELECCIONAR")
            {
                ok = false;
                errorProvider1.SetError(dropubicacion, "Elige una Ubicación Valida");
            }
            if (textnumasignado.Text == "")
            {
                ok = false;
                errorProvider1.SetError(textnumasignado, "El Campo no puede estar vacío");
            }
            if (textnomasignado.Text == "")
            {
                ok = false;
                errorProvider1.SetError(textnomasignado, "El Campo no puede estar vacío");
            }
            if (dvg.RowCount == 0)
            {
                ok = false;
                errorProvider1.SetError(dvg, "No puede estar Vacío");
            }
            return ok;
        }
        private void borrarmensajeerror()
        {

            errorProvider1.SetError(textclaveauditor, "");
            errorProvider1.SetError(textnomauditor, "");
            errorProvider1.SetError(dropubicacion, "");
            errorProvider1.SetError(textnumasignado, "");
            errorProvider1.SetError(textnomasignado, "");
            errorProvider1.SetError(dvg, "");
        }- 👋 Hi, I’m @EmperatrizRL
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
EmperatrizRL/EmperatrizRL is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

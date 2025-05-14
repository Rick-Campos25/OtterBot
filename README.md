OtterBot is a custom AI-powered chatbot application designed to help California State University Monterey Bay (CSUMB) students with questions about education abroad. Built with a modern, customizable graphical interface using CustomTkinter, this assistant connects to the OpenAI API (ChatGPT) and provides clear, friendly responses in real time. The chat history can be exported to PDF, and users can toggle between light and dark themes for an enhanced experience.

Libraries Used:
- customtkinter (for advanced GUI design)
- tkinter.filedialog & tkinter.messagebox (for file export and popups)
- reportlab (for exporting chat history as a PDF)
- openai (to connect to the ChatGPT API)
- PIL / Pillow (for loading and displaying images)

Features:
- AI chatbot with OpenAI's GPT-4 for education abroad Q&A
- Toggle between light and dark themes
- Export chat conversation to PDF
- Custom logo/image display in the header
- Clear chat and quit options
- Responsive and modern UI using CustomTkinter

Note:
- Requires a valid OpenAI API key for functionality.
- Image file (`new.png`) must be in the same directory to display the CSUMB banner/logo.
- API key should ideally be stored securely (not hardcoded) in real-world applications.

Security Tip:
Avoid committing your OpenAI API key to public repositories. Use environment variables or external config files for sensitive data in production environments.

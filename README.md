export default function Home() {
  return (
    <main className="min-h-screen flex flex-col items-center justify-center bg-white text-gray-900 px-6 text-center font-sans max-w-xl mx-auto">
      <h1 className="text-4xl font-bold mb-8">Hi, I’m David</h1>
      <p className="mb-6 text-lg leading-relaxed">
        I’m a college student who’s really passionate about learning web design.  
        I want to help people in our neighborhood get online with simple, beautiful websites.
      </p>
      <p className="mb-6 text-lg leading-relaxed">
        Building websites is fun for me — it’s a way to combine creativity and technology.  
        I’m not a big agency or a company, just your local student trying to build skills and make some money while helping others.
      </p>
      <p className="mb-6 text-lg leading-relaxed">
        If you ever want a website made just for you — whether it’s for your small business, a hobby, or anything else —  
        I’d love to chat and see how I can help.
      </p>
      <p className="mb-6 text-lg leading-relaxed italic text-gray-600">
        Thanks for reading and supporting local talent!
      </p>
      <footer className="mt-16 text-sm text-gray-500">
        &copy; {new Date().getFullYear()} David Boling
      </footer>
    </main>
  );
}

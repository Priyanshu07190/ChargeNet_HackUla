### CarbonCreditListing Collection

```javascript
{
  _id: ObjectId,
  seller_id: ObjectId (ref: User),
  seller_name: String,
  credits_amount: Number,
  price_per_credit: Number,
  total_price: Number,
  status: 'active' | 'sold' | 'cancelled',
  buyer_id: ObjectId (ref: User),
  sold_at: Date,
  created_at: Date
}
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Contribution Guidelines

1. **Fork the Repository**
   ```bash
   git clone https://github.com/YourUsername/ChargeNet.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make Your Changes**
   - Follow existing code style
   - Write meaningful commit messages
   - Add tests for new features

4. **Test Your Changes**
   ```bash
   npm test
   npm run test:coverage
   ```

5. **Commit and Push**
   ```bash
   git commit -m "Add: Amazing new feature"
   git push origin feature/amazing-feature
   ```

6. **Open a Pull Request**
   - Describe your changes
   - Link related issues
   - Wait for review

### Code Style

- Use **TypeScript** for frontend
- Follow **ESLint** rules
- Use **Prettier** for formatting
- Write **meaningful comments**
- Keep functions **small and focused**

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👥 Team

Built with ❤️ by **Team ChargeNet**

- **Project Lead**: [Your Name]
- **Frontend Developer**: [Name]
- **Backend Developer**: [Name]
- **UI/UX Designer**: [Name]

---

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - UI Library
- [MongoDB](https://www.mongodb.com/) - Database
- [Razorpay](https://razorpay.com/) - Payment Gateway
- [Socket.io](https://socket.io/) - Real-time Communication
- [TailwindCSS](https://tailwindcss.com/) - Styling
- [Vite](https://vitejs.dev/) - Build Tool

---

##  Future Roadmap

- [ ] Mobile App (React Native)
- [ ] AI-based Route Optimization
- [ ] Integration with more payment gateways
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] Blockchain-based carbon credits
- [ ] AR navigation for finding chargers
- [ ] Fleet management for businesses
- [ ] API for third-party integrations

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

**Made with 💚 for a Sustainable Future**

[⬆ Back to Top](#-chargenet---smart-ev-charging-platform)

</div>

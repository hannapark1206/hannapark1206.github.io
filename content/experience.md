.experience-wrap {
  width: min(1360px, calc(100vw - 3rem)) !important;
  max-width: none !important;
  margin-left: 50% !important;
  transform: translateX(-50%) !important;
}

.experience-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 1.1rem;
  margin-top: 1.2rem;
  margin-bottom: 2.7rem;
}

@media (max-width: 1100px) {
  .experience-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 700px) {
  .experience-grid {
    grid-template-columns: 1fr;
  }
}

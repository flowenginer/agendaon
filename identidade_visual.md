# Identidade Visual - Vava BarberShop

## Paleta de Cores
- **Primária**: Tons de azul
  - primary-50: #f0f9ff
  - primary-100: #e0f2fe
  - primary-200: #bae6fd
  - primary-300: #7dd3fc
  - primary-400: #38bdf8
  - primary-500: #0ea5e9
  - primary-600: #0284c7
  - primary-700: #0369a1
  - primary-800: #075985
  - primary-900: #0c4a6e

- **Secundária**: Tons de cinza/azul escuro
  - secondary-50: #f8fafc
  - secondary-100: #f1f5f9
  - secondary-200: #e2e8f0
  - secondary-300: #cbd5e1
  - secondary-400: #94a3b8
  - secondary-500: #64748b
  - secondary-600: #475569
  - secondary-700: #334155
  - secondary-800: #1e293b
  - secondary-900: #0f172a

## Tipografia
- Fonte principal: font-sans (sistema)
- Títulos: font-bold, text-xl ou text-2xl
- Subtítulos: font-semibold, text-secondary-700
- Texto normal: text-secondary-800
- Texto secundário: text-secondary-500, text-sm

## Componentes
- **Botões**:
  - Primário: bg-primary-600, hover:bg-primary-700, text-white, rounded-xl, py-4, shadow-md
  - Secundário: bg-white, hover:bg-gray-50, text-secondary-700, border border-gray-200, rounded-xl, py-3, shadow-sm
  
- **Cards**:
  - Borda: border-2 border-gray-100 ou border border-gray-100
  - Cantos arredondados: rounded-xl ou rounded-lg
  - Sombra: shadow-sm
  - Hover: card-hover (transform: translateY(-2px), shadow)
  - Selecionado: border: 2px solid #0ea5e9, background-color: #f0f9ff

- **Ícones**:
  - Font Awesome 6
  - Cores: text-primary-600 (azul) ou text-secondary-500 (cinza)

## Layout
- Container principal: max-w-lg mx-auto bg-white min-h-screen shadow-sm
- Fundo da página: bg-gray-50
- Header: bg-gradient-to-r from-primary-700 to-primary-800 text-white
- Padding padrão: p-6 ou px-6 py-4
- Espaçamento entre elementos: mb-6, space-y-3, space-y-4

## Animações
- fadeIn: opacidade 0 a 1 com translateY(10px) a translateY(0)
- Transições: transition-all duration-200

## Elementos Interativos
- Opções selecionáveis: Mudança de cor de fundo e borda quando selecionado
- Barra de progresso: Azul com transição suave
- Campos de formulário: focus:ring-2 focus:ring-primary-300 focus:border-primary-300


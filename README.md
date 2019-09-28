# UI3

3D UI lib for SwiftUI



~~~~swift
import SwiftUI
import UI3

struct ContentView: View {
    var body: some View {
        ZStack {
            Color.gray
                .edgesIgnoringSafeArea(.all)
            UI3 {
                HStack {
                    Box()
                        .chamferRadius(0.05)
                    VStack {
                        Box()
                            .chamferRadius(0.05)
                        ZStack {
                            Box()
                                .chamferRadius(0.05)
                            Box()
                                .chamferRadius(0.05)
                        }
                    }
                }
            }
        }
    }
}
~~~~
